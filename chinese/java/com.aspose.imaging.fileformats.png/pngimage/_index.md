---
title: "PngImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们功能强大的 API 操作便携式网络图形（PNG）光栅图像，支持压缩级别以及包括灰度、索引颜色、真彩色和 alpha 通道在内的多种色深。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

使用我们功能强大的 API 操作 Portable Network Graphics (PNG) 光栅图像，支持压缩级别以及包括灰度、索引颜色、真彩色和 alpha 通道在内的多种色深。无缝处理 XMP 元数据，实现全面的图像元数据管理，同时轻松加载 PNG 图像，执行多种操作，应用滤镜，并将图像转换为其他文件格式，以获得最佳的灵活性和定制性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | 通过提供宽度和高度参数，初始化 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新对象。 |
| [PngImage(String path)](#PngImage-java.lang.String-) | 使用 path 参数指定要加载的图像文件位置，构造 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。 |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | 通过提供光栅图像作为参数，创建 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。 |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | 通过指定图像文件路径和颜色类型，初始化 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。 |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | 通过指定光栅图像和颜色类型，创建 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。 |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | 通过使用流进行初始化，创建 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。 |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | 实例化 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的全新实例，指定所需的宽度、高度和颜色类型参数。 |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | 初始化 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例，结合 PNG 选项以及宽度和高度参数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 检索图像的每像素位数值。 |
| [getHeight()](#getHeight--) | 获取图像的像素高度。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 检索或修改图像的水平分辨率。 |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 检索或修改图像的水平分辨率。 |
| [getFileFormat()](#getFileFormat--) | 检索与图像实例关联的文件格式。 |
| [getRawDataFormat()](#getRawDataFormat--) | 访问图像的原始数据格式。 |
| [getVerticalResolution()](#getVerticalResolution--) | 提供对图像垂直分辨率的访问。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 提供对图像垂直分辨率的访问。 |
| [getWidth()](#getWidth--) | 允许检索图像的像素宽度，提供有关其尺寸的关键信息。 |
| [hasTransparentColor()](#hasTransparentColor--) | 提供一个布尔值，指示图像是否包含透明颜色。 |
| [hasAlpha()](#hasAlpha--) | 返回一个布尔值，指示图像是否具有 alpha 通道，以决定其透明度。 |
| [getTransparentColor()](#getTransparentColor--) | 检索图像的透明颜色（如果存在）。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 提供一个布尔值，指示图像是否包含透明颜色。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | 修改图像的透明颜色（如果存在）。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 检索一个布尔值，指示图像是否具有背景颜色。 |
| [getBackgroundColor()](#getBackgroundColor--) | 检索图像的背景颜色（如果已指定）。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 检索一个布尔值，指示图像是否具有背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 检索图像的背景颜色（如果已指定）。 |
| [getInterlaced()](#getInterlaced--) | 检索一个布尔值，指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为交错模式，这决定图像数据是否以渐进方式存储，以实现更快的加载或传输。 |
| [isInterlaced()](#isInterlaced--) | 获取一个值，指示此图像实例是否为交错。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 获取默认选项。 |
| [getOriginalOptions()](#getOriginalOptions--) | 根据原始文件设置获取选项。 |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// 从文件加载 PNG 图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // 将图像转换为灰度表示
    pngImage.grayscale();

    // 保存到文件。
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


通过提供宽度和高度参数来初始化 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新对象。此构造函数通过允许开发者直接指定尺寸，简化了 PNG 图像的创建，便于在其应用程序中高效管理 PNG 图像数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


使用路径参数指定要加载的图像文件位置，构造 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。此构造函数使开发者能够方便地通过从文件加载来创建 PNG 图像，简化了在其应用程序中使用 PNG 图像的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载图像的路径。 |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


通过提供光栅图像作为参数，创建 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。此构造函数允许开发者直接使用现有的光栅图像初始化 PNG 图像对象，简化了在其应用程序中使用 PNG 图像的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


通过指定图像文件的路径和颜色类型，初始化 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。此构造函数便于从具有不同颜色类型的文件创建 PNG 图像，提供了处理各种图像格式的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载图像的路径。 |
| colorType | int | 颜色类型。 |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


通过指定光栅图像和颜色类型，创建 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。此构造函数使开发者能够在指定所需颜色类型的同时，直接将光栅图像转换为 PNG 格式，提供了颜色表示的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| colorType | int | 颜色类型。 |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


通过使用流进行初始化，创建 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例。此构造函数允许开发者直接从流中加载 PNG 图像，提供了从不同来源获取图像的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流。 |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


实例化一个全新的 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类对象，指定所需的宽度、高度和颜色类型参数。此构造函数实现了快速创建具有定制尺寸和颜色配置的 PNG 图像，便于在各种应用和工作流中实现高效的图像生成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |
| colorType | int | 颜色类型。 |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


初始化 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 类的新实例，结合 PNG 选项以及宽度和高度参数。此构造函数使开发者能够创建具有可定制设置和尺寸的 PNG 图像，为多种使用场景下的图像生成提供了灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | PNG 选项。 |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像的每像素位数值。此属性提供有关图像颜色深度的关键信息，使开发者能够了解图像数据中细节和颜色准确度的水平。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像的像素高度。此属性返回图像的垂直尺寸，使开发者能够确定其在垂直轴上的像素大小。

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


获取或修改图像的水平分辨率。此属性表示图像水平轴上每英寸的像素数。调整此分辨率可能会影响图像在打印或显示时的实际尺寸。

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // 获取 PngImage 的水平和垂直分辨率。
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//输出可能如下所示：
//水平分辨率（每英寸像素数）：96.0
//垂直分辨率（每英寸像素数）：96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


获取或修改图像的水平分辨率。此属性表示图像水平轴上每英寸的像素数。调整此分辨率可能会影响图像在打印或显示时的实际尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


检索与图像实例关联的文件格式。此属性提供有关文件类型的基本信息，使得能够根据特定格式要求高效地处理和操作文件。

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


访问图像的原始数据格式。此属性提供对图像数据内部结构的了解，可用于高级图像处理任务或格式转换。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// 要加载的 PNG 图像。
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// 输出可能如下所示：
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


提供对图像垂直分辨率的访问。开发者可以使用此属性获取或修改分辨率设置，该设置指示图像垂直轴上每英寸的像素数 (PPI)。

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // 获取 PngImage 的水平和垂直分辨率。
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//输出可能如下所示：
//水平分辨率（每英寸像素数）：96.0
//垂直分辨率（每英寸像素数）：96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


提供对图像垂直分辨率的访问。开发者可以使用此属性获取或修改分辨率设置，该设置指示图像垂直轴上每英寸的像素数 (PPI)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


允许获取图像的像素宽度，提供其尺寸的基本信息。此属性常被开发者用于确定图像宽度，从而基于其大小执行各种操作。

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


提供一个布尔值，指示图像是否包含透明颜色。此属性对需要处理透明度的应用程序至关重要，使开发者能够判断是否需要对图像中的透明区域进行额外处理。

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


返回一个布尔值，指示图像是否具有 alpha 通道，从而决定其透明度。此属性对于需要处理透明度的应用程序很有用，允许开发者判断是否需要额外的处理来处理图像中的透明区域。

**Returns:**
boolean - 如果此实例具有 alpha，则为 `true`；否则为 `false`。

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// 帮助类
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// 以下是主要示例
Utils utils = new Utils();

// 获取所有受支持的 PNG 颜色类型。
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// 输出如下：
// 灰度 PNG 图像不支持 alpha 通道
// 真彩色 PNG 图像不支持 alpha 通道
// 索引颜色 PNG 图像不支持 alpha 通道
// 带 alpha 通道的灰度 PNG 图像支持 alpha 通道
// 带 alpha 通道的真彩色 PNG 图像支持 alpha 通道
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


检索图像的透明颜色（如果存在）。此属性对于需要精确处理图像中透明区域的应用程序非常有价值，允许开发者访问并操作使用的特定透明颜色。

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


提供一个布尔值，指示图像是否包含透明颜色。此属性对需要处理透明度的应用程序至关重要，使开发者能够判断是否需要对图像中的透明区域进行额外处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 创建一个 100x100 像素的真彩色 PNG 图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // 所有红色像素将被视为完全透明。
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // 所有透明像素将拥有背景颜色。
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // 用白色填充整个图像。
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // 用透明颜色填充图像左上角的四分之一区域。
    // 这会使左上角的四分之一区域呈现背景颜色。
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


修改图像的透明颜色（如果存在）。此属性对于需要精确处理图像中透明区域的应用程序非常有价值，允许开发者访问并操作使用的特定透明颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 创建一个 100x100 像素的真彩色 PNG 图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // 所有红色像素将被视为完全透明。
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // 所有透明像素将拥有背景颜色。
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // 用白色填充整个图像。
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // 用透明颜色填充图像左上角的四分之一区域。
    // 这会使左上角的四分之一区域呈现背景颜色。
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


检索一个布尔值，指示图像是否具有背景颜色。此属性对于需要确定图像是否包含背景颜色的应用程序很有用，这在合成、渲染或导出等各种处理任务中可能很重要。

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


检索图像的背景颜色（如果已指定）。此属性对于需要识别并可能操作图像背景颜色的应用程序很有帮助。

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


检索一个布尔值，指示图像是否具有背景颜色。此属性对于需要确定图像是否包含背景颜色的应用程序很有用，这在合成、渲染或导出等各种处理任务中可能很重要。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 创建一个 100x100 像素的真彩色 PNG 图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // 所有红色像素将被视为完全透明。
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // 所有透明像素将拥有背景颜色。
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // 用白色填充整个图像。
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // 用透明颜色填充图像左上角的四分之一区域。
    // 这会使左上角的四分之一区域呈现背景颜色。
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


检索图像的背景颜色（如果已指定）。此属性对于需要识别并可能操作图像背景颜色的应用程序很有帮助。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 创建一个 100x100 像素的真彩色 PNG 图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // 所有红色像素将被视为完全透明。
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // 所有透明像素将拥有背景颜色。
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // 用白色填充整个图像。
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // 用透明颜色填充图像左上角的四分之一区域。
    // 这会使左上角的四分之一区域呈现背景颜色。
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


检索一个布尔值，指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为交错模式，这决定图像数据是否以渐进方式存储，以实现更快的加载或传输。

**Returns:**
boolean - 如果为隔行扫描则为 `true`；否则为 `false`。
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


获取一个值，指示此图像实例是否为交错。

值：如果此图像实例为隔行扫描则为 `true`；否则为 `false`。

**Returns:**
boolean - 指示此图像实例是否为隔行扫描的值。
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


获取默认选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | java.lang.Object[] | 参数。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 `DataStreamSupporter.Save(string)` 方法保存，它将生成每像素 8 位的输出 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 `Image.Save(string, ImageOptionsBase)` 方法。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
