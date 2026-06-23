---
title: "WebPImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用我们的 API 操作 WebP 栅格图像，利用其现代特性实现无损和有损压缩，确保在减小文件大小的同时获得最佳图像质量。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

使用我们的 API 操作 WebP 栅格图像，利用其现代特性实现无损和有损压缩，确保在减小文件大小的同时获得最佳图像质量。无缝处理扩展文件格式、动画和 alpha 通道，同时轻松更新尺寸、等比例缩放、裁剪、旋转、应用滤镜、调整图像参数，并转换为其他图像格式，以实现多功能的网页图像优化。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | 实例化一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用提供的流源进行初始化。 |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | 创建一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用流和指定的加载选项，以便灵活处理 WebP 图像数据。 |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | 实例化一个全新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用提供的文件源进行初始化。 |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | 创建一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用文件和指定的加载选项，以实现灵活处理 WebP 图像数据。 |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | 实例化一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用提供的 rasterImage 对象进行初始化。 |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | 创建一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用 rasterImage 对象和指定的加载选项，以实现灵活处理图像数据。 |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | 实例化一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用指定宽度和高度的空白图像。 |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | 创建一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，使用空白图像和指定的加载选项。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOptions()](#getOptions--) | 检索或修改与指定属性关联的选项，以实现对行为和设置的精细定制。 |
| [getPages()](#getPages--) | 访问图像中的 WebP 块，允许对底层块结构进行详细检查或操作。 |
| [getPageCount()](#getPageCount--) | 检索指定文档的总页数，以便高效地导航和管理多页内容。 |
| [getFileFormat()](#getFileFormat--) | 获取与图像关联的文件格式值，提供图像存储格式的信息。 |
| [hasAlpha()](#hasAlpha--) | 检索图像是否包含 alpha 通道，以指示透明信息的存在。 |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | 向图像追加新页面，扩展其内容并容纳额外的视觉元素。 |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | 将新的 WebP 块合并到图像中，丰富其内容并促进高级图像操作。 |
| [clearBlocks()](#clearBlocks--) | 清除图像中所有现有的 WebP 块，为后续的修改或添加提供干净的起点。 |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | 在图像中的指定索引处插入新的 WebP 块，以实现对块序列的精确控制。 |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | 从图像中移除指定的 WebP 块，以便高效管理图像数据结构。 |
| [getOriginalOptions()](#getOriginalOptions--) | 根据原始文件设置获取选项。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | 围绕中心按指定角度旋转图像，同时按比例调整大小并应用指定的背景颜色参数。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整图像大小，改变其尺寸并保持纵横比。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 按比例调整图像宽度，同时保持其纵横比。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 按比例调整图像高度，并保持纵横比以实现一致的缩放。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 仅对图像中的活动帧应用旋转、翻转或两者的操作。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | 对当前图像进行抖动处理，以降低颜色条纹并提升视觉质量。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 使用指定的矩形区域裁剪图像，去除不需要的部分并保留所需内容。 |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | 通过左、右、上、下偏移裁剪图像，有效选择图像中的感兴趣区域。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义的阈值对图像进行二值化，将其转换为二进制图像，像素根据相对于阈值的强度被分类为前景或背景。 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳阈值。 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 自适应阈值算法（基于积分图像阈值）对图像进行二值化。 |
| [grayscale()](#grayscale--) | 使用 Bradley 自适应阈值算法（基于积分图像阈值）对图像进行二值化。 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 对图像应用伽马校正，调整像素强度以实现所需的亮度和色彩平衡。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 使用红、绿、蓝通道的单独系数对图像进行伽马校正，以实现对色彩平衡和对比度的精细调节。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 实现对图像的 `brightness` 调整，允许修改整体亮度水平。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 增强 [Image](../../com.aspose.imaging/image) 的对比度，放大亮部和暗部之间的差异。 |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | 过滤指定矩形内的内容，应用指定的图像处理滤镜以增强或修改所选区域。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 根据指定设置调整图像大小，实现对尺寸、纵横比和缩放行为的精确控制。 |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// 从文件加载 WebP 图像。
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // 保存为 PNG
    // 请注意，由于 PNG 不是多页格式，只有活动帧会被存储为 PNG。
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


实例化一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类对象，使用提供的流源进行初始化。利用此构造函数可直接从流无缝创建 WebP 图像对象，实现对 WebP 图像数据的高效处理和操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流式 WebP 图像。 |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


使用流和指定的加载选项创建一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，以便灵活处理 WebP 图像数据。在应用程序中使用此构造函数可从流无缝初始化 WebP 图像对象，并根据需要自定义加载参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流式 WebP 图像。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


实例化一个全新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类对象，使用提供的文件源进行初始化。利用此构造函数可直接从文件无缝创建 WebP 图像对象，简化在应用程序中加载和操作 WebP 图像数据的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 文件 WebP 图像的路径。 |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


使用文件和指定的加载选项创建一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类实例，以实现对 WebP 图像数据的灵活处理。利用此构造函数可从文件无缝初始化 WebP 图像对象，并根据应用程序需求自定义加载参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 文件 WebP 图像的路径。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


实例化一个新的 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类对象，使用提供的 rasterImage 对象进行初始化。此构造函数可实现栅格图像到 WebP 格式的无缝转换，提升在应用程序中对图像数据的高效处理和操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


使用 rasterImage 对象和指定的加载选项创建 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类的新实例，以实现对图像数据的灵活处理。利用此构造函数可无缝地从栅格图像初始化 WebP 图像对象，并根据应用程序的需求自定义加载参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


使用指定宽度和高度的空白图像实例化 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类的新实例。此构造函数允许创建空白的 WebP 图像，为后续的图像操作和内容生成提供基础。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像宽度 |
| height | int | 图像高度。 |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | 选项。 |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


使用空白图像和指定的加载选项创建 [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) 类的新实例。此构造函数允许使用可自定义的加载参数初始化 WebP 图像，为应用程序中的图像创建和操作提供灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像宽度 |
| height | int | 图像高度。 |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | 选项。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


检索或修改与指定属性关联的选项，以实现对行为和设置的精细定制。利用此属性可无缝访问和操控可配置参数，促进在应用程序功能中的多样化控制和优化。

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


访问图像中的 WebP 块，以便详细检查或操作底层块结构。利用此属性可分析或修改 WebP 图像数据中的各个块，促进在应用程序中的高级图像处理技术。

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


检索指定文档的总页数，以便高效导航和管理多页内容。集成此功能可提升用户体验，实现对完整文档结构的无缝访问。

**Returns:**
int - 页数。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


访问与图像关联的文件格式值，提供图像存储格式的信息。利用此属性确定图像的文件格式，以便在应用程序中进行兼容性检查和特定格式的处理。

**Returns:**
long - 文件格式的值
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


检索图像是否包含 alpha 通道，以指示是否存在透明信息。利用此属性可确定图像是否包含透明度，从而在应用程序中适当地处理和处理与 alpha 相关的操作。

**Returns:**
boolean - 如果存在 alpha 通道则为 `true`。

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 如果活动的 TIFF 帧具有 alpha 通道，则整个 TIFF 图像被视为具有 alpha 通道。
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


向图像追加新页面，扩展其内容并容纳更多视觉元素。将此方法集成到应用程序中，以实现动态页面管理，支持无缝创建和增强多页文档或图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | 要添加的页面。 |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


在图像中加入新的 WebP 块，丰富其内容并促进高级图像操作。将此方法集成到应用程序中，以动态增强 WebP 图像数据的结构和复杂度，实现对图像渲染的精确控制和优化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | 要添加的 Webp 块。 |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// 默认帧加上 36 + 36 个额外帧。
createOptions.setAnimLoopCount(36 + 36 + 1);

// 创建一个 100x100 像素的 WebP 图像。
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // 第一个圆是红色的
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // 第二个圆是黑色的
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // 逐渐增大红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // 逐渐增大黑色弧形的角度并抹去红色弧形。
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // 保存为 WebP 文件
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


清除图像中所有现有的 WebP 块，以便为后续的修改或添加提供干净的起点。利用此方法可有效重置 WebP 图像数据中的块结构，确保在应用程序中对图像内容进行最佳的管理和组织。

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


在图像中指定索引处插入新的 WebP 块，以实现对块顺序的精确控制。将此方法集成到应用程序中，可无缝地将额外的 WebP 块合并到图像数据结构中，促进高级图像处理和优化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 零基索引的元素，`block` 将被插入的位置。 |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | 要添加的 Webp 块。 |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


从图像中移除指定的 WebP 块，以实现对图像数据结构的高效管理。利用此方法可通过消除不必要的块或组件来简化应用程序中的图像处理工作流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | 要移除的块。 |

--------------------

注意：如果不将 `block` 添加到其他 WebPImage，请务必记得释放它。 |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) 方法保存，它将生成每像素 8 位的 PNG 输出图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将它们作为第二个参数传递给 [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) 方法。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


围绕图像中心按指定角度旋转图像，同时按比例调整大小并应用指定的背景颜色参数。将此方法纳入图像处理工作流，以实现具有可自定义背景颜色的精确变换，确保在应用程序中获得最佳的视觉呈现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度，以度为单位。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则，尺寸保持不变，仅 `` 图像内容被旋转。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


调整图像大小，改变其尺寸并保持纵横比。将此方法集成到图像处理工作流中，以动态缩放图像以满足应用程序中各种显示或存储需求。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


按比例调整图像的宽度，同时保持其纵横比。将此方法集成到您的图像处理工作流中，以动态地以一致的比例调整图像大小，确保在应用程序中实现最佳显示或存储。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| resizeType | int | 调整的类型。 |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


按比例调整图像的高度，同时保持其纵横比以实现一致的缩放。将此方法集成到您的图像处理工作流中，以动态地以统一的比例调整图像大小，确保在应用程序中实现最佳显示或存储。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整的类型。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


仅对图像中的活动帧应用旋转、翻转或两者操作。将此方法集成到您的图像处理工作流中，以实现对单个帧的精确操作，增强在应用程序中对帧转换的灵活性和控制力。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


对当前图像执行抖动处理，以减少颜色条纹并提升视觉质量。将此方法集成到您的图像处理工作流中，以实现颜色之间更平滑的过渡，改善图像在应用程序中的整体外观。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 抖动的自定义调色板。 |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


使用指定的矩形区域裁剪图像，去除不需要的部分并保留所需内容。将此方法集成到您的图像处理工作流中，以精确提取并聚焦图像中感兴趣的特定区域，提升各种应用的清晰度和构图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


通过左右、上下位移对图像进行裁剪，有效选择图像中的感兴趣区域。利用此方法动态提取图像所需部分，并根据应用程序的需求调整其构图和焦点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | int | 左位移。 |
| rightShift | int | 右位移。 |
| topShift | int | 上位移。 |
| bottomShift | int | 下位移。 |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


使用预定义阈值对图像进行二值化，将其转换为二进制图像，根据像素相对于阈值的强度将其分类为前景或背景。将此方法集成到您的图像处理工作流中，以促进分割和特征提取任务，提升后续分析的准确性和效率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为 (byte)255，否则为 0。 |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


使用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳阈值。将此方法集成到您的图像处理工作流中，以实现有效的分割和特征提取，提升图像分析任务的准确性和可靠性。

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


使用 Bradley 自适应阈值算法结合积分图对图像进行二值化。此方法根据图像邻域动态计算局部阈值，增强对不同光照条件的适应性，并确保后续处理任务的稳健分割。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素的亮度差是该像素与以其为中心的 s × s 窗口像素平均值之间的差异。 |
| windowSize | int | 以该像素为中心的 s × s 窗口的大小 |

### grayscale() {#grayscale--}
```
public void grayscale()
```


使用 Bradley 自适应阈值算法结合积分图对图像进行二值化。此方法根据图像邻域动态计算局部阈值，增强对不同光照条件的适应性，并确保后续处理任务的稳健分割。

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


对图像应用伽马校正，调整像素强度以实现所需的亮度和色彩平衡。将此方法纳入您的图像处理工作流中，以提升视觉质量并改善后续分析或显示任务的准确性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | float | 红色、绿色和蓝色通道系数的 Gamma |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


使用红、绿、蓝通道的单独系数对图像进行伽马校正，允许对色彩平衡和对比度进行精细调整。将此方法集成到您的图像处理管道中，以实现对颜色渲染的精确控制并提升视觉保真度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | float | 红色通道的伽马系数 |
| gammaGreen | float | 绿色通道的伽马系数 |
| gammaBlue | float | 蓝色通道系数的 Gamma |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


实现对图像的 `brightness` 调整，以便修改整体亮度水平。将此方法纳入图像处理工作流，以增强可见性并提升应用程序中图像的视觉质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


增强 [Image](../../com.aspose.imaging/image) 的对比度，放大明暗区域之间的差异。将此方法集成到您的图像处理工作流中，以提升视觉清晰度和整体图像质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | float | 对比度值（范围为 [-100; 100]） |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


过滤指定矩形内的内容，应用指定的图像处理滤镜以增强或修改所选区域。将此方法集成到图像操作工作流中，以在您的应用程序内实现针对性的增强或转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | 选项。 |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 对整幅图像应用矩形大小为5的中值滤波器。
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 对整幅图像应用核大小为5的双边平滑滤波器。
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 对整幅图像应用半径为5、sigma值为4.0的高斯模糊滤波器。
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 对整幅图像应用半径为5、平滑值为4.0的Gauss-Wiener滤波器。
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 对整幅图像应用长度为5、平滑值为4.0、角度为90.0度的运动Wiener滤波器。
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 对整幅图像应用核大小为5、sigma值为4.0的锐化滤波器。
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


根据指定设置调整图像大小，实现对尺寸、纵横比和缩放行为的精确控制。将此方法集成到您的图像处理工作流中，以实现针对应用程序特定需求的自定义缩放操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 调整大小的设置。 |

