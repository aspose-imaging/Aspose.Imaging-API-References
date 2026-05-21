---
title: "PsdOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa Photoshop-dokument PSD-bilder med vårt API som erbjuder mångsidiga alternativ med olika formatversioner, komprimeringsmetoder, färglägen och bitantal per färgkanal."
type: docs
weight: 40
url: /sv/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Skapa Photoshop-dokument (PSD)-bilder med vårt API, som erbjuder mångsidiga alternativ med olika formatversioner, komprimeringsmetoder, färglägen och bitantal per färgkanal. Hantera sömlöst XMP-metadata‑behållare, vilket säkerställer en omfattande bildbehandling med kraften i PSD-formatets funktioner som bildlager, lagermasker och filinformation för anpassning och kreativitet i dina designer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Initierar en ny instans av klassen `PsdOptions`. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Initierar en ny instans av klassen `PsdOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Hämta eller ange XMP-datakontainer |
| [getVersion()](#getVersion--) | Hämtar eller anger PSD-filversionen. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger PSD-filversionen. |
| [getCompressionMethod()](#getCompressionMethod--) | Hämtar eller anger PSD-komprimeringsmetoden. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Hämtar eller anger PSD-komprimeringsmetoden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar filformatets version. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Anger filformatets version. |
| [getColorMode()](#getColorMode--) | Hämtar eller anger PSD-färgläget. |
| [setColorMode(short value)](#setColorMode-short-) | Hämtar eller anger PSD-färgläget. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Hämtar eller anger bitantalet per färgkanal. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Hämtar eller anger bitantalet per färgkanal. |
| [getChannelsCount()](#getChannelsCount--) | Hämtar antalet färgkanaler. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Anger antalet färgkanaler. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Hämtar ett värde som indikerar om - Ta bort den globala textmotormyndigheten - Används för vissa textlagrade PSD-filer, endast i de fall då de inte kan öppnas i Adobe Photoshop efter bearbetning (oftast relaterat till saknade teckensnitt i textlager). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Anger ett värde som indikerar om - Ta bort den globala textmotormyndigheten - Används för vissa textlagrade PSD-filer, endast i de fall då de inte kan öppnas i Adobe Photoshop efter bearbetning (oftast relaterat till saknade teckensnitt i textlager). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Hämtar ett värde som indikerar om [refresh image preview data] - alternativ som används för att maximera kompatibiliteten med andra PSD-bildvisare. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Anger ett värde som indikerar om [refresh image preview data] - alternativ som används för att maximera kompatibiliteten med andra PSD-bildvisare. |
| [getVectorizationOptions()](#getVectorizationOptions--) | Hämtar PSD-vektoriseringsalternativen. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | Ställer in vektoriseringsalternativen för PSD. |

## Example: This example demonstrates the use of Aspose.
Detta exempel demonstrerar användningen av Aspose.Imaging för Java API för att konvertera bilder till PSD-format. För att uppnå detta mål laddar detta exempel en befintlig bild och sparar den sedan tillbaka i PSD-format.
``` java

// Skapa en instans av bildklassen och initiera den med en befintlig fil via filsökväg.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Skapa en instans av klassen PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Ställ in CompressionMethod till RLE.
    // Obs: Andra stödjade CompressionMethod är CompressionMethod.RAW [Ingen komprimering]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Ställ in ColorMode till GrayScale.
    // Obs: Andra stödjade ColorModes är ColorModes.Bitmap och ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Spara bilden till disk med de angivna PsdOptions-inställningarna.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som lager i den resulterande PSD-filen.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Initierar en ny instans av klassen `PsdOptions`.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Initierar en ny instans av klassen `PsdOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | Alternativen. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Hämta eller ange XMP-datakontainer

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger PSD-filversionen.

Värde: PSD-filens version.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger PSD-filversionen.

Värde: PSD-filens version.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definiera en linjär blå-genomskinlig gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll PNG-bilden med den linjära blå-genomskinliga gradienten.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Följande alternativ kommer att användas för att spara PNG-bilden i PSD-format.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Antalet bitar per kanal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Antalet kanaler. En kanal för varje färgkomponent R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Färgläget
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Ingen komprimering.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Standardversionen är 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE-komprimeringen möjliggör att minska storleken på den resulterande bilden.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Utdata kan se ut så här:
    // Storleken på PSD-bilden med RAW-komprimering: 40090.
    // Storleken på PSD-bilden med RLE-komprimering: 16185.
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


Hämtar eller anger PSD-komprimeringsmetoden.

Värde: Komprimeringsmetoden.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


Hämtar eller anger PSD-komprimeringsmetoden.

Värde: Komprimeringsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |


**Example: This example demonstrates the use of Aspose.**
Detta exempel demonstrerar användningen av Aspose.Imaging för Java API för att konvertera bilder till PSD-format. För att uppnå detta mål laddar detta exempel en befintlig bild och sparar den sedan tillbaka i PSD-format.
``` java

// Skapa en instans av bildklassen och initiera den med en befintlig fil via filsökväg.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Skapa en instans av klassen PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Ställ in CompressionMethod till RLE.
    // Obs: Andra stödjade CompressionMethod är CompressionMethod.RAW [Ingen komprimering]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Ställ in ColorMode till GrayScale.
    // Obs: Andra stödjade ColorModes är ColorModes.Bitmap och ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Spara bilden till disk med de angivna PsdOptions-inställningarna.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Hämtar filformatets version. Det kan vara PSD eller PSB.

Värde: Filformatets version.

**Returns:**
byte - filformatets version.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Ställer in filformatets version. Den kan vara PSD eller PSB.

Värde: Filformatets version.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | filformatets version. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


Hämtar eller anger PSD-färgläget.

Värde: Färgläget.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


Hämtar eller anger PSD-färgläget.

Värde: Färgläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |


**Example: This example demonstrates the use of Aspose.**
Detta exempel demonstrerar användningen av Aspose.Imaging för Java API för att konvertera bilder till PSD-format. För att uppnå detta mål laddar detta exempel en befintlig bild och sparar den sedan tillbaka i PSD-format.
``` java

// Skapa en instans av bildklassen och initiera den med en befintlig fil via filsökväg.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Skapa en instans av klassen PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Ställ in CompressionMethod till RLE.
    // Obs: Andra stödjade CompressionMethod är CompressionMethod.RAW [Ingen komprimering]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Ställ in ColorMode till GrayScale.
    // Obs: Andra stödjade ColorModes är ColorModes.Bitmap och ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Spara bilden till disk med de angivna PsdOptions-inställningarna.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Hämtar eller anger bitantalet per färgkanal.

Värde: Antalet bitar per färgkanal.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Hämtar eller anger bitantalet per färgkanal.

Värde: Antalet bitar per färgkanal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definiera en linjär blå-genomskinlig gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll PNG-bilden med den linjära blå-genomskinliga gradienten.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Följande alternativ kommer att användas för att spara PNG-bilden i PSD-format.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Antalet bitar per kanal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Antalet kanaler. En kanal för varje färgkomponent R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Färgläget
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Ingen komprimering.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Standardversionen är 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE-komprimeringen möjliggör att minska storleken på den resulterande bilden.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Utdata kan se ut så här:
    // Storleken på PSD-bilden med RAW-komprimering: 40090.
    // Storleken på PSD-bilden med RLE-komprimering: 16185.
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Hämtar antalet färgkanaler.

**Returns:**
short - Antalet färgkanaler.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Anger antalet färgkanaler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | Antalet färgkanaler. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definiera en linjär blå-genomskinlig gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll PNG-bilden med den linjära blå-genomskinliga gradienten.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Följande alternativ kommer att användas för att spara PNG-bilden i PSD-format.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Antalet bitar per kanal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Antalet kanaler. En kanal för varje färgkomponent R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Färgläget
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Ingen komprimering.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Standardversionen är 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE-komprimeringen möjliggör att minska storleken på den resulterande bilden.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Utdata kan se ut så här:
    // Storleken på PSD-bilden med RAW-komprimering: 40090.
    // Storleken på PSD-bilden med RLE-komprimering: 16185.
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Hämtar ett värde som indikerar om - Ta bort den globala textmotorn - Används för vissa textlagrade PSD-filer, endast i det fall de inte kan öppnas i Adobe Photoshop efter bearbetning (mest relaterat till saknade teckensnitt i textlager). Efter att ha använt detta alternativ måste användaren göra följande i den öppnade Photoshop-filen: Meny \"Text\" -> \"Process absent fonts\". Efter den operationen kommer all text att visas igen. Observera att denna operation kan orsaka vissa slutgiltiga layoutändringar.

**Returns:**
boolean - `true` om [remove global text engine resource]; annars, `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Ställer in ett värde som indikerar om - Ta bort den globala textmotorn - Används för vissa textlagrade PSD-filer, endast i det fall de inte kan öppnas i Adobe Photoshop efter bearbetning (mest relaterat till saknade teckensnitt i textlager). Efter att ha använt detta alternativ måste användaren göra följande i den öppnade Photoshop-filen: Meny \"Text\" -> \"Process absent fonts\". Efter den operationen kommer all text att visas igen. Observera att denna operation kan orsaka vissa slutgiltiga layoutändringar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om [remove global text engine resource]; annars, `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Hämtar ett värde som indikerar om [refresh image preview data] - alternativ som används för att maximera kompatibiliteten med andra PSD-bildvisare.

**Returns:**
boolean - `true` om [refresh image preview data]; annars, `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Anger ett värde som indikerar om [refresh image preview data] - alternativ som används för att maximera kompatibiliteten med andra PSD-bildvisare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om [refresh image preview data]; annars, `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


Hämtar PSD-vektoriseringsalternativen.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


Ställer in vektoriseringsalternativen för PSD.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | PSD-vektoriseringens alternativ. |

