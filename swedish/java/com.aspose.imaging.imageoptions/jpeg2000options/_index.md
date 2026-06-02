---
title: "Jpeg2000Options"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa JPEG2000 JP2-bildfiler med vårt API som utnyttjar avancerad vågformsteknik för kodning av förlustfritt innehåll."
type: docs
weight: 25
url: /sv/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Skapa JPEG2000 (JP2)-bildfiler med vårt API, som utnyttjar avancerad vågformsteknik för kodning av förlustfritt innehåll. Dra nytta av stöd för olika kodekar, inklusive irreversibel och förlustfri komprimering, samt XMP-metadatabehållare, vilket säkerställer mångsidighet och högkvalitativ bildskapning anpassad efter dina behov.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Initierar en ny instans av klassen `Jpeg2000Options`. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Initierar en ny instans av klassen `Jpeg2000Options`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getComments()](#getComments--) | Hämtar eller anger Jpeg-kommentarmarkörerna. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Hämtar eller anger Jpeg-kommentarmarkörerna. |
| [getCodec()](#getCodec--) | Hämtar eller anger JPEG2000-kodeken. |
| [setCodec(int value)](#setCodec-int-) | Hämtar eller anger JPEG2000-kodeken. |
| [getCompressionRatios()](#getCompressionRatios--) | Hämtar eller anger arrayen av komprimeringsförhållanden. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Hämtar eller anger arrayen av komprimeringsförhållanden. |
| [getIrreversible()](#getIrreversible--) | Hämtar ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-komprimering (standard) ska användas. |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Anger ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-komprimering (standard) ska användas. |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. I själva verket kommer bara en sida att rasteriseras eftersom JPEG 2000 inte är ett flersidigt format.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Initierar en ny instans av klassen `Jpeg2000Options`.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Initierar en ny instans av klassen `Jpeg2000Options`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Jpeg2000-filformatalternativen att kopiera inställningar från. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Hämtar eller anger Jpeg-kommentarmarkörerna.

**Returns:**
java.lang.String[] - Jpeg-kommentarmarkörerna.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Hämtar eller anger Jpeg-kommentarmarkörerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] | Jpeg-kommentarmarkörerna. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Hämtar eller anger JPEG2000-kodeken.

**Returns:**
int - JPEG2000-kodeken
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Hämtar eller anger JPEG2000-kodeken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | JPEG2000-kodeken |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll hela bilden med rött.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Använd den irreversibla Discrete Wavelet Transform 9-7
    saveOptions.setIrreversible(true);

    // JP2 är "container"-formatet för JPEG 2000-kodströmmar.
    // J2K är rå komprimerad data, utan en omslag.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Spara till en fil
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Hämtar eller anger arrayen av komprimeringsförhållanden. Olika komprimeringsförhållanden för på varandra följande lager. Den hastighet som anges för varje kvalitetsnivå är den önskade komprimeringsfaktorn. Minskande förhållanden krävs.

**Returns:**
int[] - Komprimeringsförhållandena.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Hämtar eller anger arrayen av komprimeringsförhållanden. Olika komprimeringsförhållanden för på varandra följande lager. Den hastighet som anges för varje kvalitetsnivå är den önskade komprimeringsfaktorn. Minskande förhållanden krävs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Komprimeringsförhållandena. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Hämtar ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-komprimering (standard) ska användas.

**Returns:**
boolean - ett värde som indikerar om du använder den irreversibla DWT 9-7 (true) eller förlustfri DWT 5-3-komprimering
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Anger ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-komprimering (standard) ska användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om du använder den irreversibla DWT 9-7 (true) eller förlustfri DWT 5-3-komprimering |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll hela bilden med rött.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Använd den irreversibla Discrete Wavelet Transform 9-7
    saveOptions.setIrreversible(true);

    // JP2 är "container"-formatet för JPEG 2000-kodströmmar.
    // J2K är rå komprimerad data, utan en omslag.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Spara till en fil
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

