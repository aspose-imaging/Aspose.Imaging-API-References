---
title: BitmapCompression
second_title: Aspose.Imaging for Java API Reference
description: Specifies different bitmap compression methods.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Specifies different bitmap compression methods.
## Fields

| Field | Description |
| --- | --- |
| [Rgb](#Rgb) | No compression. |
| [Rle8](#Rle8) | RLE 8-bit/pixel compression. |
| [Rle4](#Rle4) | RLE 4-bit/pixel compression. |
| [Bitfields](#Bitfields) | RGB bit fields. |
| [Jpeg](#Jpeg) | JPEG compression. |
| [Png](#Png) | PNG compression. |
| [AlphaBitfields](#AlphaBitfields) | RGBA bit fields. |
| [Dxt1](#Dxt1) | DXT1 compression. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Load a PNG image from a file.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP image is saved with transparency support by default.
    // If you want to explicitly specify such mode, the BmpOptions's Compression property should be set to BitmapCompression.Bitfields.
    // The BitmapCompression.Bitfields compression method is the default compression method in the BmpOptions.
    // So the same result of exporting a Bmp image with transparency can be achieved by either one of the following ways.
    // With an implicit default options:
    pngImage.save(outputPathPng);
    // With an explicit default options:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Specifying the BitmapCompression.Bitfields compression method:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Load a PNG image from a file.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP image is saved with transparency support by default, that is achieved by using the BitmapCompression.Bitfields compression method.
    // To save a BMP image with the Rgb compression method, the BmpOptions with the Compression property set to BitmapCompression.Rgb should be specified.
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


No compression.

### Rle8 {#Rle8}
```
public static final long Rle8
```


RLE 8-bit/pixel compression. Can be used only with 8-bit/pixel bitmaps.

### Rle4 {#Rle4}
```
public static final long Rle4
```


RLE 4-bit/pixel compression. Can be used only with 4-bit/pixel bitmaps.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


RGB bit fields. Can be used only with 16 and 32-bit/pixel bitmaps.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


JPEG compression. The bitmap contains a JPEG image.

### Png {#Png}
```
public static final long Png
```


PNG compression. The bitmap contains a PNG image.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


RGBA bit fields. Can be used only with 16 and 32-bit/pixel bitmaps.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


DXT1 compression. The bitmap contains a texture.

