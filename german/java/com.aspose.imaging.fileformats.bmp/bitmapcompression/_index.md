---
title: "BitmapCompression"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt verschiedene Bitmap-Komprimierungsmethoden an."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Gibt verschiedene Bitmap-Komprimierungsmethoden an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Rgb](#Rgb) | Keine Kompression. |
| [Rle8](#Rle8) | RLE 8‑Bit/Pixel‑Kompression. |
| [Rle4](#Rle4) | RLE 4‑Bit/Pixel‑Kompression. |
| [Bitfields](#Bitfields) | RGB‑Bitfelder. |
| [Jpeg](#Jpeg) | JPEG‑Kompression. |
| [Png](#Png) | PNG‑Kompression. |
| [AlphaBitfields](#AlphaBitfields) | RGBA‑Bitfelder. |
| [Dxt1](#Dxt1) | DXT1‑Kompression. |

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

### Rgb {#Rgb}
```
public static final long Rgb
```


Keine Kompression.

### Rle8 {#Rle8}
```
public static final long Rle8
```


RLE 8‑Bit/Pixel‑Kompression. Kann nur mit 8‑Bit/Pixel‑Bitmaps verwendet werden.

### Rle4 {#Rle4}
```
public static final long Rle4
```


RLE 4‑Bit/Pixel‑Kompression. Kann nur mit 4‑Bit/Pixel‑Bitmaps verwendet werden.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


RGB‑Bitfelder. Kann nur mit 16‑ und 32‑Bit/Pixel‑Bitmaps verwendet werden.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


JPEG‑Kompression. Das Bitmap enthält ein JPEG‑Bild.

### Png {#Png}
```
public static final long Png
```


PNG‑Kompression. Das Bitmap enthält ein PNG‑Bild.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


RGBA‑Bitfelder. Kann nur mit 16‑ und 32‑Bit/Pixel‑Bitmaps verwendet werden.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


DXT1‑Kompression. Das Bitmap enthält eine Textur.

