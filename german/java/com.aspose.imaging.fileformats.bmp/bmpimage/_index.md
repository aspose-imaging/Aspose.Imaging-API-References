---
title: "BmpImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Sie können Bitmap BMP und Device Independent Bitmap DIB-Dateien mühelos handhaben, was eine effiziente Manipulation und Verarbeitung von Rasterbildern ermöglicht."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

Sie können Bitmap (BMP) und Device Independent Bitmap (DIB) Dateien mühelos handhaben, was eine effiziente Manipulation und Verarbeitung von Rasterbildern ermöglicht. Durch verschiedene Bildoperationen rationalisiert diese API den Arbeitsablauf und bietet Entwicklern ein zuverlässiges Toolkit für die Arbeit mit BMP- und DIB-Formaten in ihren Softwareanwendungen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | Beginnen Sie, die BmpImage-Klasse mühelos zu verwenden, mit diesem Konstruktor, der eine neue Instanz initialisiert. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Erstellen Sie mühelos eine neue Instanz der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-Klasse mit diesem Konstruktor, wobei Sie angegebene Parameter wie Pfad, bitsPerPixel und Kompression verwenden. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Beginnen Sie, die [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-Klasse mühelos zu verwenden, indem Sie mit diesem Konstruktor eine neue Instanz initialisieren und dabei einen Stream als Eingabe verwenden. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Beginnen Sie, mit der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-Klasse nahtlos zu arbeiten, indem Sie eine neue Instanz mit einem Stream erstellen und dabei angegebene Parameter wie bitsPerPixel und Kompression verwenden. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Erstellen Sie mühelos eine neue Instanz der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-Klasse, indem Sie sie mit einem RasterImage-Objekt initialisieren. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Beginnen Sie, mit der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-Klasse nahtlos zu arbeiten, indem Sie eine neue Instanz mit einem rasterImage erstellen und dabei angegebene Parameter wie bitsPerPixel und Kompression verwenden. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Beginnen Sie, die [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-Klasse mühelos zu verwenden, indem Sie eine neue Instanz mit angegebenen Breiten- und Höhenparametern erstellen. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Beginnen Sie, die [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-Klasse nahtlos zu verwenden, indem Sie eine neue Instanz mit Parametern wie Breite, Höhe, Bit-Tiefe und Palette initialisieren. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Erstellen Sie mühelos eine neue Instanz der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse mit diesem Konstruktor und geben Sie Parameter wie Breite, Höhe, bitsPerPixel und Palette an. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Greifen Sie schnell auf wichtige Details Ihres Bitmap-Bildes mit dieser einfachen Funktion zu. |
| [getFileFormat()](#getFileFormat--) | Rufen Sie den Dateiformatwert einfach mit dieser benutzerfreundlichen Eigenschaft ab. |
| [getRawDataFormat()](#getRawDataFormat--) | Ermitteln Sie einfach das Format Ihrer Rohdaten mit dieser benutzerfreundlichen Funktion. |
| [getRawLineSize()](#getRawLineSize--) | Greifen Sie schnell auf die Größe jeder Rohzeile in Bytes mit dieser einfachen Eigenschaft zu. |
| [getCompression()](#getCompression--) | Rufen Sie mühelos den für das Bild verwendeten Kompressionstyp mit dieser Eigenschaft ab. |
| [getWidth()](#getWidth--) | Greifen Sie einfach auf die Breite des Bildes mit dieser Eigenschaft zu. |
| [getHeight()](#getHeight--) | Rufen Sie mühelos die Höhe des Bildes mit dieser Eigenschaft ab. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Greifen Sie mit Leichtigkeit auf die Anzahl der Bits pro Pixel für das Bild zu, indem Sie diese Eigenschaft verwenden. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Diese Eigenschaft ermöglicht es Ihnen, die horizontale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage) Objekts, gemessen in Pixel pro Zoll, einfach zu erhalten oder festzulegen. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Diese Eigenschaft ermöglicht es Ihnen, die horizontale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage) Objekts, gemessen in Pixel pro Zoll, einfach zu erhalten oder festzulegen. |
| [getVerticalResolution()](#getVerticalResolution--) | Rufen Sie mit dieser Eigenschaft die vertikale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage) Objekts, gemessen in Pixel pro Zoll, einfach ab oder setzen Sie sie. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Rufen Sie mit dieser Eigenschaft die vertikale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage) Objekts, gemessen in Pixel pro Zoll, einfach ab oder setzen Sie sie. |
| [hasAlpha()](#hasAlpha--) | Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Passen Sie die Auflösung Ihres [RasterImage](../../com.aspose.imaging/rasterimage) mühelos mit dieser benutzerfreundlichen Methode an. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Rufen Sie die Standardoptionen mühelos mit dieser einfachen Methode ab. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// Erstelle ein BMP-Bild mit 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Füllen Sie das Bild mit einem einfachen linearen Rot-Schwarz-Verlauf.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

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


## Example: The example shows how to export a BmpImage with the Rgb compression type.

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


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


Beginnen Sie mühelos mit der BmpImage-Klasse zu arbeiten, indem Sie diesen Konstruktor verwenden, der eine neue Instanz initialisiert. Perfekt für Entwickler, die schnell und effizient mit [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Objekten loslegen möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Erstellen Sie mühelos eine neue Instanz der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse mit diesem Konstruktor und verwenden Sie dabei angegebene Parameter wie Pfad, bitsPerPixel und Kompression. Ideal für Entwickler, die BmpImage-Objekte schnell und effizient initialisieren möchten, mit präziser Kontrolle über Bildeigenschaften.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |
| bitsPerPixel | int | Die Bits pro Pixel. |
| Kompression | long | Die zu verwendende Kompression. |
| horizontalResolution | double | Die horizontale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |
| verticalResolution | double | Die vertikale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Beginnen Sie mühelos mit der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse, indem Sie mit diesem Konstruktor eine neue Instanz initialisieren und dabei einen Stream als Eingabe verwenden. Perfekt für Entwickler, die eine bequeme Möglichkeit suchen, mit BmpImage-Objekten aus verschiedenen Datenquellen zu arbeiten, und dabei Flexibilität und einfache Integration gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Arbeiten Sie nahtlos mit der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse, indem Sie eine neue Instanz mithilfe eines Streams erstellen und dabei angegebene Parameter wie bitsPerPixel und Kompression verwenden. Perfekt für Entwickler, die eine unkomplizierte Methode zum Umgang mit BmpImage-Objekten suchen und dabei Flexibilität und Effizienz in ihren Projekten sicherstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |
| bitsPerPixel | int | Die Bits pro Pixel. |
| Kompression | long | Die zu verwendende Kompression. |
| horizontalResolution | double | Die horizontale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |
| verticalResolution | double | Die vertikale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Erstellen Sie mühelos eine neue Instanz der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse, indem Sie sie mit einem RasterImage-Objekt initialisieren. Perfekt für Entwickler, die vorhandene Rasterbilder nahtlos in das BmpImage-Format konvertieren möchten, um Kompatibilität und einfache Integration in ihre Projekte zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Pixel‑ und Palettendaten initialisiert werden sollen. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Arbeiten Sie nahtlos mit der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse, indem Sie eine neue Instanz mit einem rasterImage erstellen und dabei angegebene Parameter wie bitsPerPixel und Kompression verwenden. Perfekt für Entwickler, die eine unkomplizierte Methode zum Umgang mit BmpImage-Objekten suchen und dabei Flexibilität und Effizienz in ihren Projekten sicherstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Pixel‑ und Palettendaten initialisiert werden sollen. |
| bitsPerPixel | int | Die Bits pro Pixel. |
| Kompression | long | Die zu verwendende Kompression. |
| horizontalResolution | double | Die horizontale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |
| verticalResolution | double | Die vertikale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Beginnen Sie mühelos mit der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse, indem Sie eine neue Instanz mit angegebenen Breiten- und Höhenparametern erstellen. Ideal für Entwickler, die eine bequeme Möglichkeit suchen, BmpImage-Objekte mit benutzerdefinierten Abmessungen zu erzeugen, und dabei Flexibilität und einfache Integration in ihre Projekte gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Beginnen Sie mit der Verwendung der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse nahtlos, indem Sie eine neue Instanz mit Parametern wie Breite, Höhe, Bit-Tiefe und Palette initialisieren. Perfekt für Entwickler, die eine unkomplizierte Möglichkeit suchen, BmpImage-Objekte mit benutzerdefinierten Abmessungen und Farbkonfigurationen zu erstellen, um Flexibilität und Effizienz in ihren Projekten zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |
| bitsPerPixel | int | Die Bits pro Pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Erstellen Sie mühelos eine neue Instanz der [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) Klasse mit diesem Konstruktor, wobei Sie Parameter wie Breite, Höhe, bitsPerPixel und Palette angeben. Perfekt für Entwickler, die eine bequeme Möglichkeit suchen, BmpImage-Objekte mit benutzerdefinierten Abmessungen und Farbkonfigurationen zu erzeugen, um Flexibilität und einfache Integration in ihre Projekte zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |
| bitsPerPixel | int | Die Bits pro Pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |
| Kompression | long | Die zu verwendende Kompression. |
| horizontalResolution | double | Die horizontale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |
| verticalResolution | double | Die vertikale Auflösung. Hinweis: Aufgrund der Rundung kann die resultierende Auflösung leicht von der übergebenen abweichen. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Greifen Sie schnell auf wesentliche Details Ihres Bitmap-Bildes mit dieser einfachen Funktion zu. Perfekt für Entwickler, die Header-Informationen für ihre Bilder abrufen müssen.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Die Anzahl der für die Anzeige des Bitmaps erforderlichen Palettenfarben: 0
//Die Anzahl der im Bitmap verwendeten Palettenfarben: 0
//Die Bitmap-Kompression: 0
//Die Bitmap-Höhe: 100
//Die Bitmap-Breite: 100
//Die Größe der rohen Bitmap-Daten in Bytes: 40000
//Die Anzahl der Ebenen: 1
//Die horizontale Auflösung des Bitmaps in Pixel pro Meter: 0
//Die vertikale Auflösung des Bitmaps in Pixel pro Meter: 0
//Die Anzahl der Bits pro Pixel: 32
//Die zusätzlichen Bitmasken: null
//Die Header-Größe in Bytes: 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie den Dateiformatwert einfach über diese benutzerfreundliche Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf Informationen zum Dateiformat benötigen.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// Die Hilfsklasse, die im nachfolgenden Hauptbeispiel verwendet wird.
class Utils {
    // Die Hilfsmethode, um eine Zeichenkettenrepräsentation des Dateiformats zu erhalten.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Hier ist das Hauptbeispiel.
Utils utils = new Utils();

// Erstellen Sie ein 32‑bpp BMP‑Bild mit 100 × 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Erstellen Sie ein 24‑bpp BMP‑Bild mit 100 × 100 px.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// In den meisten Fällen unterstützt BMP keinen Alphakanal, sodass die Ausgabe wahrscheinlich so aussieht:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, verwendete Kanäle: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, verwendete Kanäle: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Erhalten Sie einfach das Format Ihrer Rohdaten mit dieser benutzerfreundlichen Funktion. Perfekt für Entwickler, die schnell auf wichtige Informationen über ihr Datenformat zugreifen möchten.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Sie könnten in Erwägung ziehen, die SetResolution‑Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Das Pixel-Format: Rgb24Bpp, verwendete Kanäle: 8,8,8
//Die rohe Zeilengröße in Bytes: 1500
//Die Bitmap-Kompression: 0
//Die Bitmap-Breite: 500
//Die Bitmap-Höhe: 500
//Die Anzahl der Bits pro Pixel: 24
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
//Auflösungswerte auf 96 dpi setzen
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Greifen Sie schnell auf die Größe jeder Rohzeile in Bytes mit dieser unkomplizierten Eigenschaft zu. Ideal für Entwickler, die Rohbilddaten effizient verarbeiten müssen.

**Returns:**
int - Die Rohzeilengröße in Bytes.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Sie könnten in Erwägung ziehen, die SetResolution‑Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Das Pixel-Format: Rgb24Bpp, verwendete Kanäle: 8,8,8
//Die rohe Zeilengröße in Bytes: 1500
//Die Bitmap-Kompression: 0
//Die Bitmap-Breite: 500
//Die Bitmap-Höhe: 500
//Die Anzahl der Bits pro Pixel: 24
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
//Auflösungswerte auf 96 dpi setzen
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Rufen Sie den für das Bild verwendeten Kompressionstyp mühelos mit dieser Eigenschaft ab. Perfekt für Entwickler, die schnell Informationen über die Bildkompression benötigen.

**Returns:**
long - Die Bildkompression [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// Die Hilfsklasse, die im nachfolgenden Hauptbeispiel verwendet wird.
class Utils {
    // Die Hilfsmethode, um eine Zeichenkettenrepräsentation des Dateiformats zu erhalten.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Hier ist das Hauptbeispiel.
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// Erstellen Sie eine monochrome Palette, die nur rote und grüne Farben enthält.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // Erstellen Sie ein 8‑bpp BMP‑Bild mit 100 × 100 px.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Füllen Sie das gesamte Bild mit Rot.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Speichern Sie das Bild in einen Stream, um die Ausgabegröße des Bildes zu erhalten.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// Die Ausgabe könnte so aussehen:
// Die Kompression=RGB
// Die Anzahl der Bits pro Pixel=8
// Die Bildabmessungen=100 × 100
// Die Rohzeilengröße=100
// Die Ausgabengröße in Bytes=11078
// ---------------------------------------------
// Die Kompression=RLE8
// Die Anzahl der Bits pro Pixel=8
// Die Bildabmessungen=100 × 100
// Die Rohzeilengröße=100
// Die Ausgabengröße in Bytes=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Greifen Sie einfach auf die Breite des Bildes mit dieser Eigenschaft zu. Ideal für Entwickler, die schnelle Informationen über die Bildabmessungen suchen.

**Returns:**
int - Die Bildbreite in Pixeln.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Sie könnten in Erwägung ziehen, die SetResolution‑Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Das Pixel-Format: Rgb24Bpp, verwendete Kanäle: 8,8,8
//Die rohe Zeilengröße in Bytes: 1500
//Die Bitmap-Kompression: 0
//Die Bitmap-Breite: 500
//Die Bitmap-Höhe: 500
//Die Anzahl der Bits pro Pixel: 24
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
//Auflösungswerte auf 96 dpi setzen
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Rufen Sie die Höhe des Bildes mühelos mit dieser Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf Informationen über die Bildabmessungen benötigen.

**Returns:**
int - Die Bildhöhe in Pixeln.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Sie könnten in Erwägung ziehen, die SetResolution‑Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Das Pixel-Format: Rgb24Bpp, verwendete Kanäle: 8,8,8
//Die rohe Zeilengröße in Bytes: 1500
//Die Bitmap-Kompression: 0
//Die Bitmap-Breite: 500
//Die Bitmap-Höhe: 500
//Die Anzahl der Bits pro Pixel: 24
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
//Auflösungswerte auf 96 dpi setzen
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Greifen Sie mit Leichtigkeit auf die Anzahl der Bits pro Pixel für das Bild zu, indem Sie diese Eigenschaft verwenden. Perfekt für Entwickler, die schnelle Informationen über Bildqualität und Farbtiefe suchen.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Sie könnten in Erwägung ziehen, die SetResolution‑Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Das Pixel-Format: Rgb24Bpp, verwendete Kanäle: 8,8,8
//Die rohe Zeilengröße in Bytes: 1500
//Die Bitmap-Kompression: 0
//Die Bitmap-Breite: 500
//Die Bitmap-Höhe: 500
//Die Anzahl der Bits pro Pixel: 24
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
//Auflösungswerte auf 96 dpi setzen
//Die horizontale Auflösung, in Pixel pro Zoll: 96.012
//Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Diese Eigenschaft ermöglicht es Ihnen, die horizontale Auflösung, gemessen in Pixel pro Zoll, des [RasterImage](../../com.aspose.imaging/rasterimage)-Objekts einfach zu erhalten oder festzulegen. Ideal für Entwickler, die eine präzise Kontrolle über die Bildauflösung für ihre Anwendungen benötigen.

**Returns:**
double - Die horizontale Auflösung.

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können erwägen, die \#setResolution(double, double).setResolution(double, double)-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Horizontale und vertikale Auflösung des BmpImage abrufen
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 0.0
// Die vertikale Auflösung, in Pixel pro Zoll: 0.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 96.012
// Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Diese Eigenschaft ermöglicht es Ihnen, die horizontale Auflösung, gemessen in Pixel pro Zoll, des [RasterImage](../../com.aspose.imaging/rasterimage)-Objekts einfach zu erhalten oder festzulegen. Ideal für Entwickler, die eine präzise Kontrolle über die Bildauflösung für ihre Anwendungen benötigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die horizontale Auflösung. |

--------------------

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können erwägen, die \#setResolution(double, double).setResolution(double, double)-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Einfach die vertikale Auflösung, gemessen in Pixel pro Zoll, dieses [RasterImage](../../com.aspose.imaging/rasterimage)-Objekts mit dieser Eigenschaft abrufen oder festlegen. Perfekt für Entwickler, die eine präzise Kontrolle über die Bildauflösung in ihren Anwendungen benötigen.

**Returns:**
double - Die vertikale Auflösung.

--------------------

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können erwägen, die \#setResolution(double, double).setResolution(double, double)-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Horizontale und vertikale Auflösung des BmpImage abrufen
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 0.0
// Die vertikale Auflösung, in Pixel pro Zoll: 0.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 96.012
// Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Einfach die vertikale Auflösung, gemessen in Pixel pro Zoll, dieses [RasterImage](../../com.aspose.imaging/rasterimage)-Objekts mit dieser Eigenschaft abrufen oder festlegen. Perfekt für Entwickler, die eine präzise Kontrolle über die Bildauflösung in ihren Anwendungen benötigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die vertikale Auflösung. |

--------------------

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können erwägen, die \#setResolution(double, double).setResolution(double, double)-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat.

**Returns:**
boolean – ein Wert, der angibt, ob diese Instanz Alpha hat.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Passen Sie die Auflösung Ihres [RasterImage](../../com.aspose.imaging/rasterimage) mühelos mit dieser benutzerfreundlichen Methode an. Perfekt für Entwickler, die eine präzise Kontrolle über die Bildauflösung in ihren Anwendungen suchen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | double | Die horizontale Auflösung in Punkten pro Zoll (dpi) des [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Die vertikale Auflösung in Punkten pro Zoll (dpi) des [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Horizontale und vertikale Auflösung des BmpImage abrufen
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 0.0
// Die vertikale Auflösung, in Pixel pro Zoll: 0.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 96.012
// Die vertikale Auflösung, in Pixel pro Zoll: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Rufen Sie die Standardoptionen mühelos mit dieser unkomplizierten Methode ab. Ideal für Entwickler, die schnellen Zugriff auf die Standard‑Bildeinstellungen oder -Konfigurationen benötigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | java.lang.Object[] | Die Argumente. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
