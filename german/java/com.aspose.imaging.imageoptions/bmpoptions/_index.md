---
title: "BmpOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für BMP- und DIB-Rasterbildformat-Erstellungsoptionen bietet Entwicklern ein vielseitiges Werkzeugset zur Erzeugung benutzerdefinierter Bitmap BMP- und Device Independent Bitmap DIB-Bilder."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

Die API für BMP- und DIB-Rasterbildformat-Erstellungsoptionen bietet Entwicklern ein vielseitiges Werkzeugset zur Erzeugung benutzerdefinierter Bitmap (BMP)- und Device Independent Bitmap (DIB)-Bilder. Mit dieser API können Sie Bildmerkmale wie Bits pro Pixel, Komprimierungsgrad und Komprimierungstyp präzise festlegen und die Ausgabe an spezifische Anforderungen anpassen. Diese funktionsreiche API ermöglicht es Entwicklern, hochqualitative, angepasste Rasterbilder mit Leichtigkeit und Flexibilität für vielfältige Anwendungen zu erstellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Initialisiert eine neue Instanz der `BmpOptions`-Klasse. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | Initialisiert eine neue Instanz der `BmpOptions`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ruft die Bits‑pro‑Pixel‑Anzahl des Bildes ab oder legt sie fest. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Ruft die Bits‑pro‑Pixel‑Anzahl des Bildes ab oder legt sie fest. |
| [getCompression()](#getCompression--) | Ruft den Komprimierungstyp ab. |
| [setCompression(long value)](#setCompression-long-) | Legt den Komprimierungstyp fest. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Dieses Beispiel demonstriert die Verwendung verschiedener Klassen aus dem SaveOptions‑Namespace für Exportzwecke. Ein Bild vom Typ Gif wird in eine Instanz von Image geladen und anschließend in mehrere Formate exportiert.
``` java
String dir = "c:\\temp\\";

//Laden Sie ein vorhandenes Bild (vom Typ Gif) in eine Instanz der Image‑Klasse.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportieren Sie in das BMP-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportieren Sie in das JPEG-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportieren Sie in das PNG-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportieren Sie in das TIFF-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportieren Sie nur die ersten beiden Seiten. Tatsächlich wird nur eine Seite gerastert, da BMP kein Mehrseitiges Format ist.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Initialisiert eine neue Instanz der `BmpOptions`-Klasse.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Initialisiert eine neue Instanz der `BmpOptions`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | Die BMP-Optionen. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ruft die Bits‑pro‑Pixel‑Anzahl des Bildes ab oder legt sie fest.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Ruft die Bits‑pro‑Pixel‑Anzahl des Bildes ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Bits‑pro‑Pixel‑Anzahl des Bildes. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // BmpOptions erstellen
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Verwende 8 Bit pro Pixel, um die Größe des Ausgabebildes zu reduzieren.
    saveOptions.setBitsPerPixel(8);

    // Setzen Sie die nächstgelegene 8‑Bit‑Farbpalette, die die maximale Anzahl von Bildpixeln abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Ohne Kompression speichern.
    // Sie können auch RLE‑8‑Kompression verwenden, um die Größe des Ausgabebildes zu reduzieren.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Setze die horizontale und vertikale Auflösung auf 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Ruft den Komprimierungstyp ab. Der Standard‑Komprimierungstyp ist [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), der das Speichern eines [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) mit Transparenz ermöglicht.

Wert: Der Komprimierungstyp.

**Returns:**
long - der Komprimierungstyp.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Legt den Kompressionstyp fest. Der Standard‑Kompressionstyp ist [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), der das Speichern eines [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) mit Transparenz ermöglicht.

Wert: Der Komprimierungstyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | der Kompressionstyp. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // BmpOptions erstellen
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Verwende 8 Bit pro Pixel, um die Größe des Ausgabebildes zu reduzieren.
    saveOptions.setBitsPerPixel(8);

    // Setzen Sie die nächstgelegene 8‑Bit‑Farbpalette, die die maximale Anzahl von Bildpixeln abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Ohne Kompression speichern.
    // Sie können auch RLE‑8‑Kompression verwenden, um die Größe des Ausgabebildes zu reduzieren.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Setze die horizontale und vertikale Auflösung auf 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Lade ein PNG‑Bild aus einer Datei.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP‑Bild wird standardmäßig mit Transparenzunterstützung gespeichert.
    // Wenn Sie diesen Modus explizit angeben möchten, sollte die Compression‑Eigenschaft von BmpOptions auf BitmapCompression.Bitfields gesetzt werden.
    // Die Kompressionsmethode BitmapCompression.Bitfields ist die Standardkompressionsmethode in BmpOptions.
    // Das gleiche Ergebnis beim Exportieren eines Bmp‑Bildes mit Transparenz kann also auf eine der folgenden Arten erzielt werden.
    // Mit impliziten Standardoptionen:
    pngImage.save(outputPathPng);
    // Mit expliziten Standardoptionen:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Angabe der Kompressionsmethode BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Lade ein PNG‑Bild aus einer Datei.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP‑Bild wird standardmäßig mit Transparenzunterstützung gespeichert, was durch die Verwendung der Kompressionsmethode BitmapCompression.Bitfields erreicht wird.
    // Um ein BMP‑Bild mit der Rgb‑Kompressionsmethode zu speichern, sollten die BmpOptions mit der Compression‑Eigenschaft auf BitmapCompression.Rgb gesetzt werden.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

