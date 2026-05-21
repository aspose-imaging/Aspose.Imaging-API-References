---
title: "BitmapCompression"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger olika bitmap-komprimeringsmetoder."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Anger olika bitmap-komprimeringsmetoder.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Rgb](#Rgb) | Ingen komprimering. |
| [Rle8](#Rle8) | RLE 8-bit/pixel-komprimering. |
| [Rle4](#Rle4) | RLE 4-bit/pixel-komprimering. |
| [Bitfields](#Bitfields) | RGB-bitfält. |
| [Jpeg](#Jpeg) | JPEG-komprimering. |
| [Png](#Png) | PNG-komprimering. |
| [AlphaBitfields](#AlphaBitfields) | RGBA-bitfält. |
| [Dxt1](#Dxt1) | DXT1-komprimering. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Läs in en PNG-bild från en fil.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP-bild sparas med transparensstöd som standard.
    // Om du vill ange sådant läge explicit, bör BmpOptions's Compression property sättas till BitmapCompression.Bitfields.
    // BitmapCompression.Bitfields-komprimeringsmetoden är standardkomprimeringsmetoden i BmpOptions.
    // Samma resultat av att exportera en Bmp-bild med transparens kan uppnås på någon av följande sätt.
    // Med implicita standardalternativ:
    pngImage.save(outputPathPng);
    // Med explicita standardalternativ:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Specificera BitmapCompression.Bitfields-komprimeringsmetoden:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Läs in en PNG-bild från en fil.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP-bild sparas med transparensstöd som standard, vilket uppnås genom att använda BitmapCompression.Bitfields-komprimeringsmetoden.
    // För att spara en BMP-bild med Rgb-komprimeringsmetoden bör BmpOptions med Compression property satt till BitmapCompression.Rgb anges.
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


Ingen komprimering.

### Rle8 {#Rle8}
```
public static final long Rle8
```


RLE 8-bit/pixel-komprimering. Kan endast användas med 8-bit/pixel-bitmapar.

### Rle4 {#Rle4}
```
public static final long Rle4
```


RLE 4-bit/pixel-komprimering. Kan endast användas med 4-bit/pixel-bitmapar.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


RGB-bitfält. Kan endast användas med 16- och 32-bit/pixel-bitmapar.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


JPEG-komprimering. Bitmapen innehåller en JPEG-bild.

### Png {#Png}
```
public static final long Png
```


PNG-komprimering. Bitmapen innehåller en PNG-bild.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


RGBA-bitfält. Kan endast användas med 16- och 32-bit/pixel-bitmapar.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


DXT1-komprimering. Bitmapen innehåller en textur.

