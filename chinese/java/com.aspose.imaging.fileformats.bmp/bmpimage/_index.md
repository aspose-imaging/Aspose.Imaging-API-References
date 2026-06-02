---
title: "BmpImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "您可以轻松处理 Bitmap BMP 和 Device Independent Bitma DIB 文件，促进对栅格图像的高效操作和处理。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

您可以轻松处理 Bitmap (BMP) 和 Device Independent Bitmap (DIB) 文件，促进对栅格图像的高效操作和处理。对图像执行各种操作时，此 API 简化工作流，为开发人员提供可靠的工具包，以在其软件应用中使用 BMP 和 DIB 格式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | 使用此构造函数轻松开始使用 BmpImage 类，该构造函数会初始化一个新实例。 |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | 使用此构造函数轻松创建 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类的新实例，使用指定的参数，如路径、bitsPerPixel 和 compression。 |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | 通过此构造函数初始化新实例，使用流作为输入，轻松开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。 |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | 通过使用流创建新实例，并指定 bitsPerPixel 和 compression 等参数，顺畅地开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。 |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | 通过使用 RasterImage 对象初始化，轻松创建 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类的新实例。 |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | 通过使用 rasterImage 创建新实例，并指定 bitsPerPixel 和 compression 等参数，顺畅地开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。 |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | 通过使用指定的宽度和高度参数创建新实例，轻松开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。 |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | 通过使用宽度、高度、位深度和调色板等参数初始化新实例，顺畅地开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。 |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | 使用此构造函数轻松创建 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类的新实例，可指定宽度、高度、bitsPerPixel 和调色板等参数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | 使用此简洁函数快速获取位图图像的关键细节。 |
| [getFileFormat()](#getFileFormat--) | 使用此用户友好的属性轻松检索文件格式值。 |
| [getRawDataFormat()](#getRawDataFormat--) | 通过此用户友好函数轻松获取原始数据的格式。 |
| [getRawLineSize()](#getRawLineSize--) | 使用此简洁属性快速获取每行原始数据的字节大小。 |
| [getCompression()](#getCompression--) | 使用此属性轻松检索图像使用的压缩类型。 |
| [getWidth()](#getWidth--) | 使用此属性轻松获取图像的宽度。 |
| [getHeight()](#getHeight--) | 使用此属性轻松检索图像的高度。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 使用此属性轻松获取图像的每像素位数。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 此属性允许您轻松获取或设置 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的水平分辨率（以每英寸像素数计）。 |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 此属性允许您轻松获取或设置 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的水平分辨率（以每英寸像素数计）。 |
| [getVerticalResolution()](#getVerticalResolution--) | 使用此属性轻松获取或设置该 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的垂直分辨率（以每英寸像素数计）。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 使用此属性轻松获取或设置该 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的垂直分辨率（以每英寸像素数计）。 |
| [hasAlpha()](#hasAlpha--) | 获取一个值，指示此实例是否具有 alpha 通道。 |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | 使用此用户友好方法轻松调整您的 [RasterImage](../../com.aspose.imaging/rasterimage) 的分辨率。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 使用此简洁方法轻松检索默认选项。 |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 BMP 图像。
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // 使用简单的线性红黑渐变填充图像。
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


使用此构造函数轻松开始使用 BmpImage 类并初始化新实例。非常适合希望快速高效使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 对象的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 加载图像的路径以及用于初始化像素和调色板数据的路径。 |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


使用此构造函数轻松创建 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类的新实例，可指定路径、bitsPerPixel 和压缩等参数。非常适合希望快速高效初始化 BmpImage 对象并精确控制图像特性的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 加载图像的路径以及用于初始化像素和调色板数据的路径。 |
| bitsPerPixel | int | 每像素位数。 |
| 压缩 | long | 要使用的压缩方式。 |
| horizontalResolution | double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |
| verticalResolution | double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


通过此构造函数初始化新实例并使用流作为输入，轻松开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。非常适合希望从各种数据源方便地使用 BmpImage 对象的开发者，确保灵活性和易于集成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流以及用于初始化像素和调色板数据的流。 |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


通过使用流创建新实例并指定 bitsPerPixel 和压缩等参数，顺畅地开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。非常适合寻求简洁方式处理 BmpImage 对象的开发者，确保项目的灵活性和高效性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流以及用于初始化像素和调色板数据的流。 |
| bitsPerPixel | int | 每像素位数。 |
| 压缩 | long | 要使用的压缩方式。 |
| horizontalResolution | double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |
| verticalResolution | double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


通过使用 RasterImage 对象初始化，轻松创建 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类的新实例。非常适合希望无缝将现有光栅图像转换为 BmpImage 格式的开发者，确保兼容性并易于集成到项目中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于初始化像素和调色板数据的图像。 |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


通过使用 rasterImage 创建新实例并指定 bitsPerPixel 和压缩等参数，顺畅地开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。非常适合寻求简洁方式处理 BmpImage 对象的开发者，确保项目的灵活性和高效性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于初始化像素和调色板数据的图像。 |
| bitsPerPixel | int | 每像素位数。 |
| 压缩 | long | 要使用的压缩方式。 |
| horizontalResolution | double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |
| verticalResolution | double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


通过指定宽度和高度参数创建新实例，轻松开始使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。非常适合希望方便生成自定义尺寸 BmpImage 对象的开发者，确保项目的灵活性和易于集成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


通过使用参数如宽度、高度、位深度和调色板来初始化新实例，开始无缝使用 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类。非常适合希望以简便方式创建具有自定义尺寸和颜色配置的 BmpImage 对象的开发者，确保项目的灵活性和高效性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |
| bitsPerPixel | int | 每像素位数。 |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


使用此构造函数，轻松创建 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) 类的新实例，指定宽度、高度、每像素位数和调色板等参数。非常适合希望以便捷方式生成具有自定义尺寸和颜色配置的 BmpImage 对象的开发者，确保项目的灵活性和易于集成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |
| bitsPerPixel | int | 每像素位数。 |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |
| 压缩 | long | 要使用的压缩方式。 |
| horizontalResolution | double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |
| verticalResolution | double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入值略有差异。 |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


使用此简洁函数，快速获取位图图像的关键细节。非常适合需要检索图像头信息的开发者。

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

//输出可能如下所示：
//显示位图所需的调色板颜色数量：0
//位图中使用的调色板颜色数量：0
//位图压缩方式：0
//位图高度：100
//位图宽度：100
//位图原始数据大小（字节）：40000
//平面数量：1
//位图的水平分辨率（像素/米）：0
//位图的垂直分辨率（像素/米）：0
//每像素位数：32
//额外位掩码：null
//头部大小（字节）：40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此用户友好的属性可以轻松获取文件格式值。对于希望快速获取文件格式信息的开发者而言，这是理想的选择。

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// 下面主示例中使用的辅助类。
class Utils {
    // 获取文件格式字符串表示的辅助方法。
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

// 以下是主要示例
Utils utils = new Utils();

// 创建一个 32 位每像素的 BMP 图像，尺寸为 100 x 100 像素。
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

// 创建一个 24 位每像素的 BMP 图像，尺寸为 100 x 100 像素。
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

// 在大多数情况下，BMP 不支持 alpha 通道，因此输出可能如下所示：
// 文件格式=BMP，原始数据格式=Rgb32Bpp，使用的通道：8,8,8,8，HasAlpha=false
// 文件格式=BMP，原始数据格式=Rgb24Bpp，使用的通道：8,8,8，HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


使用此用户友好函数，轻松获取原始数据的格式。非常适合希望快速获取数据格式关键信息的开发者。

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
        // 您可以考虑使用 SetResolution 方法一次性更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//输出可能如下所示：
//像素格式：Rgb24Bpp，使用的通道：8,8,8
//原始行大小（字节）：1500
//位图压缩方式：0
//位图宽度：500
//位图高度：500
//每像素位数：24
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
//将分辨率设置为 96 dpi
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


使用此直接属性，快速获取每行原始数据的字节大小。非常适合需要高效处理原始图像数据的开发者。

**Returns:**
int - 原始行大小（字节）。

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
        // 您可以考虑使用 SetResolution 方法一次性更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//输出可能如下所示：
//像素格式：Rgb24Bpp，使用的通道：8,8,8
//原始行大小（字节）：1500
//位图压缩方式：0
//位图宽度：500
//位图高度：500
//每像素位数：24
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
//将分辨率设置为 96 dpi
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


使用此属性轻松获取图像使用的压缩类型。非常适合需要快速获取图像压缩信息的开发者。

**Returns:**
long - 图像压缩 [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression)。

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// 下面主示例中使用的辅助类。
class Utils {
    // 获取文件格式字符串表示的辅助方法。
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

// 以下是主要示例
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

// 创建仅包含红色和绿色的单色调色板。
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // 创建一个 8 位每像素的 BMP 图像，尺寸为 100 x 100 像素。
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // 将整个图像填充为红色。
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // 将图像保存到流中以获取输出图像大小。
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

// 输出可能如下所示：
// 压缩=RGB
// 每像素位数=8
// 图像尺寸=100 x 100
// 原始行大小=100
// 输出大小（字节）=11078
// ---------------------------------------------
// 压缩=RLE8
// 每像素位数=8
// 图像尺寸=100 x 100
// 原始行大小=100
// 输出大小（字节）=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


使用此属性轻松获取图像宽度。非常适合希望快速获取图像尺寸信息的开发者。

**Returns:**
int - 图像宽度（像素）。

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
        // 您可以考虑使用 SetResolution 方法一次性更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//输出可能如下所示：
//像素格式：Rgb24Bpp，使用的通道：8,8,8
//原始行大小（字节）：1500
//位图压缩方式：0
//位图宽度：500
//位图高度：500
//每像素位数：24
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
//将分辨率设置为 96 dpi
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


使用此属性轻松获取图像高度。非常适合需要快速获取图像尺寸信息的开发者。

**Returns:**
int - 图像高度（像素）。

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
        // 您可以考虑使用 SetResolution 方法一次性更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//输出可能如下所示：
//像素格式：Rgb24Bpp，使用的通道：8,8,8
//原始行大小（字节）：1500
//位图压缩方式：0
//位图宽度：500
//位图高度：500
//每像素位数：24
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
//将分辨率设置为 96 dpi
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


使用此属性轻松获取图像的每像素位数。非常适合希望快速了解图像质量和深度的开发者。

**Returns:**
int - 图像每像素位数。

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
        // 您可以考虑使用 SetResolution 方法一次性更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//输出可能如下所示：
//像素格式：Rgb24Bpp，使用的通道：8,8,8
//原始行大小（字节）：1500
//位图压缩方式：0
//位图宽度：500
//位图高度：500
//每像素位数：24
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
//将分辨率设置为 96 dpi
//水平分辨率（每英寸像素数）：96.012
//垂直分辨率（每英寸像素数）：96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


此属性允许您轻松获取或设置 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的水平分辨率（以每英寸像素为单位）。适用于需要在其应用程序中精确控制图像分辨率的开发人员。

**Returns:**
double - 水平分辨率。

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 \#setResolution(double, double).setResolution(double, double) 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // 获取 BmpImage 的水平和垂直分辨率
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素）：0.0
// 垂直分辨率（每英寸像素）：0.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：96.012
// 垂直分辨率（每英寸像素数）：96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


此属性允许您轻松获取或设置 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的水平分辨率（以每英寸像素为单位）。适用于需要在其应用程序中精确控制图像分辨率的开发人员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 水平分辨率。 |

--------------------

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 \#setResolution(double, double).setResolution(double, double) 方法在一次调用中更新两个分辨率值。 |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


使用此属性，您可以轻松获取或设置此 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的垂直分辨率（以每英寸像素为单位）。非常适合需要在其应用程序中精确控制图像分辨率的开发人员。

**Returns:**
double - 垂直分辨率。

--------------------

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 \#setResolution(double, double).setResolution(double, double) 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // 获取 BmpImage 的水平和垂直分辨率
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素）：0.0
// 垂直分辨率（每英寸像素）：0.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：96.012
// 垂直分辨率（每英寸像素数）：96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


使用此属性，您可以轻松获取或设置此 [RasterImage](../../com.aspose.imaging/rasterimage) 对象的垂直分辨率（以每英寸像素为单位）。非常适合需要在其应用程序中精确控制图像分辨率的开发人员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 垂直分辨率。 |

--------------------

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 \#setResolution(double, double).setResolution(double, double) 方法在一次调用中更新两个分辨率值。 |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


获取一个值，指示此实例是否具有 alpha 通道。

**Returns:**
boolean - 表示此实例是否具有 alpha 的值。
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


使用此用户友好方法，轻松调整您的 [RasterImage](../../com.aspose.imaging/rasterimage) 的分辨率。非常适合希望在其应用程序中精确控制图像分辨率的开发人员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | double | 以每英寸点数表示的 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率。 |
| dpiY | double | 以每英寸点数表示的 [RasterImage](../../com.aspose.imaging/rasterimage) 的垂直分辨率。 |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // 获取 BmpImage 的水平和垂直分辨率
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素）：0.0
// 垂直分辨率（每英寸像素）：0.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：96.012
// 垂直分辨率（每英寸像素数）：96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


使用此简洁方法，轻松检索默认选项。适用于希望快速访问默认图像设置或配置的开发人员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | java.lang.Object[] | 参数。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
