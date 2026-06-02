---
title: "BitmapCompression"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指定不同的位图压缩方法。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

指定不同的位图压缩方法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Rgb](#Rgb) | 无压缩。 |
| [Rle8](#Rle8) | RLE 8 位/像素压缩。 |
| [Rle4](#Rle4) | RLE 4 位/像素压缩。 |
| [Bitfields](#Bitfields) | RGB 位字段。 |
| [Jpeg](#Jpeg) | JPEG 压缩。 |
| [Png](#Png) | PNG 压缩。 |
| [AlphaBitfields](#AlphaBitfields) | RGBA 位字段。 |
| [Dxt1](#Dxt1) | DXT1 压缩。 |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// 从文件加载 PNG 图像。
try (Image pngImage = Image.load(sourcePath))
{
    // 默认情况下，BMP 图像以支持透明度的方式保存。
    // 如果您想显式指定此模式，应将 BmpOptions 的 Compression 属性设置为 BitmapCompression.Bitfields。
    // BitmapCompression.Bitfields 压缩方法是 BmpOptions 中的默认压缩方法。
    // 因此，通过以下任一方式都可以实现导出带透明度的 Bmp 图像的相同结果。
    // 使用隐式默认选项：
    pngImage.save(outputPathPng);
    // 使用显式默认选项：
    pngImage.save(outputPathBmp, new BmpOptions());
    // 指定 BitmapCompression.Bitfields 压缩方法：
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// 从文件加载 PNG 图像。
try (Image pngImage = Image.load(sourcePath))
{
    // 默认情况下，BMP 图像以支持透明度的方式保存，这是通过使用 BitmapCompression.Bitfields 压缩方法实现的。
    // 要使用 Rgb 压缩方法保存 BMP 图像，应指定 Compression 属性设置为 BitmapCompression.Rgb 的 BmpOptions。
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


无压缩。

### Rle8 {#Rle8}
```
public static final long Rle8
```


RLE 8 位/像素压缩。只能与 8 位/像素位图一起使用。

### Rle4 {#Rle4}
```
public static final long Rle4
```


RLE 4 位/像素压缩。只能与 4 位/像素位图一起使用。

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


RGB 位字段。只能与 16 位和 32 位/像素位图一起使用。

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


JPEG 压缩。位图包含 JPEG 图像。

### Png {#Png}
```
public static final long Png
```


PNG 压缩。位图包含 PNG 图像。

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


RGBA 位字段。只能与 16 位和 32 位/像素位图一起使用。

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


DXT1 压缩。位图包含纹理。

