---
title: "Jpeg2000Options"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstellen Sie JPEG2000 JP2-Bilddateien mit unserer API, die fortschrittliche Wavelet-Technologie zur verlustfreien Codierung nutzt."
type: docs
weight: 25
url: /de/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Erstellen Sie JPEG2000 (JP2)-Bilddateien mit unserer API, die fortschrittliche Wavelet-Technologie zur verlustfreien Codierung nutzt. Profitieren Sie von der Unterstützung verschiedener Codecs, einschließlich irreversibler und verlustfreier Kompression, sowie XMP-Metadaten-Containern, die Vielseitigkeit und hochwertige Bildgenerierung gewährleisten, zugeschnitten auf Ihre Bedürfnisse.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Initialisiert eine neue Instanz der `Jpeg2000Options`-Klasse. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Initialisiert eine neue Instanz der `Jpeg2000Options`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getComments()](#getComments--) | Liest oder setzt die Jpeg-Kommentarmarker. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Liest oder setzt die Jpeg-Kommentarmarker. |
| [getCodec()](#getCodec--) | Liest oder setzt den JPEG2000-Codec |
| [setCodec(int value)](#setCodec-int-) | Liest oder setzt den JPEG2000-Codec |
| [getCompressionRatios()](#getCompressionRatios--) | Liest oder setzt das Array der Kompressionsraten. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Liest oder setzt das Array der Kompressionsraten. |
| [getIrreversible()](#getIrreversible--) | Liest einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3-Kompression (Standard) verwendet wird. |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Setzt einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3-Kompression (Standard) verwendet wird. |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportieren Sie nur die ersten beiden Seiten. Tatsächlich wird nur eine Seite gerastert, da JPEG 2000 kein Mehrseitiges Format ist.
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


Initialisiert eine neue Instanz der `Jpeg2000Options`-Klasse.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Initialisiert eine neue Instanz der `Jpeg2000Options`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Die Jpeg2000-Dateiformatoptionen, von denen Einstellungen kopiert werden sollen. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Liest oder setzt die Jpeg-Kommentarmarker.

**Returns:**
java.lang.String[] - Die Jpeg-Kommentarmarker.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Liest oder setzt die Jpeg-Kommentarmarker.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] | Die Jpeg-Kommentarmarker. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Liest oder setzt den JPEG2000-Codec

**Returns:**
int - Der JPEG2000-Codec
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Liest oder setzt den JPEG2000-Codec

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der JPEG2000-Codec |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das gesamte Bild mit Rot.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Verwenden Sie die irreversible Diskrete Wavelet-Transformation 9-7
    saveOptions.setIrreversible(true);

    // JP2 ist das "Container"-Format für JPEG 2000-Codestreams.
    // J2K ist roher komprimierter Daten, ohne Wrapper.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // In einer Datei speichern.
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Liest oder setzt das Array der Kompressionsraten. Unterschiedliche Kompressionsraten für aufeinanderfolgende Ebenen. Die für jede Qualitätsstufe angegebene Rate ist der gewünschte Kompressionsfaktor. Abnehmende Raten sind erforderlich.

**Returns:**
int[] - Die Kompressionsraten.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Liest oder setzt das Array der Kompressionsraten. Unterschiedliche Kompressionsraten für aufeinanderfolgende Ebenen. Die für jede Qualitätsstufe angegebene Rate ist der gewünschte Kompressionsfaktor. Abnehmende Raten sind erforderlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Kompressionsraten. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Liest einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3-Kompression (Standard) verwendet wird.

**Returns:**
boolean - ein Wert, der angibt, ob Sie die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3-Kompression verwenden
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Setzt einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3-Kompression (Standard) verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob Sie die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3-Kompression verwenden |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das gesamte Bild mit Rot.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Verwenden Sie die irreversible Diskrete Wavelet-Transformation 9-7
    saveOptions.setIrreversible(true);

    // JP2 ist das "Container"-Format für JPEG 2000-Codestreams.
    // J2K ist roher komprimierter Daten, ohne Wrapper.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // In einer Datei speichern.
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

