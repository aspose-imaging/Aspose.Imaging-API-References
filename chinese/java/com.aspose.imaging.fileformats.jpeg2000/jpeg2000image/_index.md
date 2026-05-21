---
title: "Jpeg2000Image"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们的 API 高效操作 JPEG2000 JP2 图像文件，支持多种每像素位深，并无缝处理包含关键图像信息的 XMP 元数据。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

使用我们的 API 高效操作 JPEG2000 (JP2) 图像文件，支持多种每像素位深，并无缝处理包含关键图像信息的 XMP 元数据。具备无损压缩功能，确保在保持文件完整性的同时实现最佳图像质量，使您能够轻松按照精确规格定制 JP2 图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | 通过使用路径初始化新实例来开始使用 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类加载您想要的图像。 |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | 通过创建同时包含文件路径和所需每像素位数参数的新实例，轻松入门使用 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类。 |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | 通过提供流对象，轻松初始化 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例。 |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | 使用流加载图像并提供每像素位数参数，初始化 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例。 |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | 创建 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例，指定宽度和高度参数。 |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | 实例化一个新的 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 对象，提供宽度、高度和图像选项参数。 |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | 使用宽度、高度和位数参数创建 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例。 |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | 使用光栅图像实例化新的 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类。 |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | 使用光栅图像和每像素位数参数初始化全新的 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 检索图像文件的格式。 |
| [getRawDataFormat()](#getRawDataFormat--) | 此属性检索图像的原始数据格式。 |
| [getRawLineSize()](#getRawLineSize--) | 此属性检索原始图像数据单行的字节大小。 |
| [getWidth()](#getWidth--) | 此属性返回图像的宽度（以像素为单位）。 |
| [getHeight()](#getHeight--) | 此属性检索图像的高度（以像素为单位）。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 此属性返回图像的深度，以每像素位数 (bpp) 为单位。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 此属性允许您检索或修改 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率，单位为每英寸像素数 (PPI)。 |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 此属性允许您检索或修改 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率，单位为每英寸像素数 (PPI)。 |
| [getVerticalResolution()](#getVerticalResolution--) | 此属性提供对 [RasterImage](../../com.aspose.imaging/rasterimage) 垂直分辨率的访问，单位为每英寸像素数 (PPI)。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 此属性提供对 [RasterImage](../../com.aspose.imaging/rasterimage) 垂直分辨率的访问，单位为每英寸像素数 (PPI)。 |
| [getComments()](#getComments--) | 此属性允许检索或更新与图像关联的注释。 |
| [setComments(String[] value)](#setComments-java.lang.String---) | 此属性允许检索或更新与图像关联的注释。 |
| [getCodec()](#getCodec--) | 此属性检索与图像关联的 JPEG2000 编解码器。 |
| [getOriginalOptions()](#getOriginalOptions--) | 根据原始文件设置检索图像选项。 |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// 加载 JPEG2000 图像。
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // 保存为 PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


通过使用要加载的图像路径初始化新实例，开始使用 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类。此构造函数可轻松访问 JPEG2000 图像，简化加载和处理图像文件的过程。提供文件路径后，您即可快速开始在应用程序中处理和操作 JPEG2000 图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 加载图像的路径以及用于初始化像素和调色板数据的路径。 |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


通过创建包含文件路径和所需每像素位数参数的新实例，轻松入门使用 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类。此构造函数允许对图像加载过程进行微调，确保兼容各种图像格式和质量设置。凭借此灵活性，您可以高效地管理和操作符合特定需求的 JPEG2000 图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 加载图像的路径以及用于初始化像素和调色板数据的路径 |
| bitsPerPixel | int | 每像素位数。 |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


通过提供流对象，轻松初始化 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例。此构造函数简化了直接从流加载 JPEG2000 图像的过程，为处理来自各种来源的图像数据提供了灵活性和便利性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流以及用于初始化像素和调色板数据的流。 |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


使用流加载图像并提供每像素位数参数来初始化 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例。此构造函数通过允许同时指定图像数据源和所需的每像素位数，提供了对图像加载过程的更精细控制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流以及用于初始化像素和调色板数据的流。 |
| bitsPerPixel | int | 每像素位数。 |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


创建 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例，指定宽度和高度参数。此构造函数允许您使用特定尺寸初始化 JPEG2000 图像，适用于需要以编程方式创建特定大小图像的场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度 |
| 高度 | int | 图像高度 |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


实例化一个新的 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 对象，提供宽度、高度和图像选项参数。此构造函数允许创建具有特定尺寸和附加选项的 JPEG2000 图像，提供了图像生成的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度 |
| 高度 | int | 图像高度 |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | 选项。 |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


使用宽度、高度和位计数参数创建 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类的新实例。此构造函数允许创建具有特定尺寸和位深度的 JPEG2000 图像，为各种成像需求提供灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度 |
| 高度 | int | 图像高度 |
| bitsCount | int | 位计数。 |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


实例化一个新的 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 类，使用栅格图像。此构造函数有助于从现有栅格图像创建 JPEG2000 图像，实现不同图像格式之间的无缝集成和转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 图像。 |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


使用光栅图像和每像素位数参数初始化一个全新的 [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) 实例。此构造函数可对生成的 JPEG2000 图像的质量和大小进行精确控制，适用于定制至关重要的场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于初始化像素和调色板数据的图像。 |
| bitsPerPixel | int | 每像素位数。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


检索图像文件的格式。此属性提供有关图像文件格式的信息。利用此属性可以编程方式确定图像文件的格式，从而根据文件格式进行适当的处理和加工。

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


此属性检索图像的原始数据格式。它提供像素数据在内存中存储方式的信息。使用此属性可了解图像的底层数据格式，这对于颜色转换、压缩或解压缩等各种图像处理操作至关重要。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


此属性检索单行原始图像数据的字节大小。它指示图像原始数据格式中单行像素占用的内存量。了解原始行大小对于内存分配、数据操作以及针对单独图像行的图像处理算法等任务至关重要。

**Returns:**
int - 原始行大小（字节）。
### getWidth() {#getWidth--}
```
public int getWidth()
```


此属性返回图像的像素宽度。它提供关于图像尺寸的基本信息，对包括缩放、裁剪和渲染在内的各种图像处理任务至关重要。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


此属性检索图像的像素高度。它是了解图像垂直尺寸的关键信息，有助于包括缩放、裁剪和渲染在内的各种图像操作。访问此属性可让用户确定图像的垂直大小，从而在应用中实现精确的布局和显示。

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


此属性返回图像的深度，以每像素位数 (bpp) 为单位。它表示每个像素存储的颜色信息量。了解图像深度对于确定图像的色彩保真度和质量至关重要。有了此信息，用户可以评估图像细节层次和颜色丰富度。

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


此属性允许检索或修改 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率，单位为每英寸像素数 (PPI)。调整此分辨率会影响图像在打印或显示时的尺寸和质量。通过设置水平分辨率，用户可以针对特定输出设备或应用优化图像，确保获得最佳视觉效果。

**Returns:**
double - 水平分辨率。

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // 获取 Jpeg2000Image 的水平和垂直分辨率。
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素数）：72.0
// 垂直分辨率（每英寸像素数）：72.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：72.0
// 垂直分辨率（每英寸像素数）：72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


此属性允许检索或修改 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率，单位为每英寸像素数 (PPI)。调整此分辨率会影响图像在打印或显示时的尺寸和质量。通过设置水平分辨率，用户可以针对特定输出设备或应用优化图像，确保获得最佳视觉效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 水平分辨率。 |

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。 |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


此属性提供对 [RasterImage](../../com.aspose.imaging/rasterimage) 垂直分辨率的访问，单位为每英寸像素数 (PPI)。修改此分辨率会影响图像在打印或显示时的质量和尺寸。通过调整垂直分辨率，用户可以针对不同的输出设备或应用优化图像，确保最佳的视觉呈现。

**Returns:**
double - 垂直分辨率。

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // 获取 Jpeg2000Image 的水平和垂直分辨率。
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素数）：72.0
// 垂直分辨率（每英寸像素数）：72.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：72.0
// 垂直分辨率（每英寸像素数）：72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


此属性提供对 [RasterImage](../../com.aspose.imaging/rasterimage) 垂直分辨率的访问，单位为每英寸像素数 (PPI)。修改此分辨率会影响图像在打印或显示时的质量和尺寸。通过调整垂直分辨率，用户可以针对不同的输出设备或应用优化图像，确保最佳的视觉呈现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 垂直分辨率。 |

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。 |

### getComments() {#getComments--}
```
public String[] getComments()
```


此属性允许检索或更新与图像关联的注释。注释提供关于图像内容的额外信息，如标注、描述或元数据。修改这些注释有助于对图像进行组织和分类，并向查看者或用户传达重要细节。

**Returns:**
java.lang.String[] - 注释。
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


此属性允许检索或更新与图像关联的注释。注释提供关于图像内容的额外信息，如标注、描述或元数据。修改这些注释有助于对图像进行组织和分类，并向查看者或用户传达重要细节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] | 注释。 |

### getCodec() {#getCodec--}
```
public int getCodec()
```


此属性检索与图像关联的 JPEG2000 编解码器。JPEG2000 编解码器负责对 JPEG2000 格式的图像数据进行编码和解码，在保持高图像质量的同时提供高效压缩。访问该编解码器可用于执行高级图像处理操作或针对特定需求优化图像压缩设置。

**Returns:**
int - 编解码器。
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


根据原始文件设置检索图像选项。此方法有助于保持原始图像的位深度和其他参数，确保一致性并保留图像数据的完整性。访问这些选项可实现对图像的无缝处理，同时保留其原始特性。例如，如果我们加载一幅 1 位每像素的黑白 PNG 图像，然后使用 [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\\#save-String-) 方法保存，它将生成 8 位每像素的 PNG 输出图像。为避免这种情况并以 1 位每像素保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\\#save-String--ImageOptionsBase-) 方法。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
