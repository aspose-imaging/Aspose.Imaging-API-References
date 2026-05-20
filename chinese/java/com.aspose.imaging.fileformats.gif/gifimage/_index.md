---
title: "GifImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Graphical Interchange Format GIF 图像文件的 API 为开发者提供了用于处理压缩光栅图像和动画 GIF 的多功能工具。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

Graphical Interchange Format (GIF) 图像文件的 API 为开发者提供了用于处理压缩光栅图像和动画 GIF 的多功能工具。提供诸如 XMP 元数据处理、颜色调色板设置、背景和透明颜色控制、不透明度设置、尺寸调整、裁剪、滤镜应用、伽马校正、对比度调节、灰度转换以及转换为其他格式等功能。此 API 使得在广泛的应用中对 GIF 图像进行无缝操作和增强成为可能。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | 使用指定的首帧和全局调色板参数初始化一个新的 [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) 对象。 |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | 使用 [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) 构造函数，制作 GIF 图像变得轻而易举。 |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | 使用 [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) 构造函数即可轻松入门。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 使用此属性即可轻松获取文件格式。 |
| [hasTrailer()](#hasTrailer--) | 使用此属性管理 GIF 文件中尾部的存在。 |
| [setTrailer(boolean value)](#setTrailer-boolean-) | 使用此属性管理 GIF 文件中尾部的存在。 |
| [isPaletteSorted()](#isPaletteSorted--) | 使用此属性控制 GIF 图像中调色板的排序。 |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | 使用此属性控制 GIF 图像中调色板的排序。 |
| [getLoopsCount()](#getLoopsCount--) | 使用此属性轻松获取循环计数。 |
| [setLoopsCount(int value)](#setLoopsCount-int-) | 使用此属性轻松获取循环计数。 |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | 使用此属性管理 GIF 图像的调色板颜色分辨率。 |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | 使用此属性管理 GIF 图像的调色板颜色分辨率。 |
| [getPageCount()](#getPageCount--) | 使用此简便属性检索图像中包含的总页数。 |
| [getPages()](#getPages--) | 通过此便利属性访问图像中的页面，允许根据需要无缝导航和操作各个页面。 |
| [getBlocks()](#getBlocks--) | 使用此属性无缝访问 GIF 块，便于轻松检索和操作图像的底层数据结构。 |
| [isInterlaced()](#isInterlaced--) | 确定图像是否为交错显示，这会影响其加载时的显示效果。 |
| [getOriginalOptions()](#getOriginalOptions--) | 检索基于原始文件设置的选项，这对于在图像处理和操作中保持真实性和一致性至关重要。 |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | 将新页面无缝合并到现有图像中，提升其内容并扩展其范围。 |
| [getActiveFrame()](#getActiveFrame--) | 使用此属性管理和操作帧，实现对 GIF 图像中活动帧的平滑导航和修改。 |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | 使用此属性管理和操作帧，实现对 GIF 图像中活动帧的平滑导航和修改。 |
| [getBackgroundColor()](#getBackgroundColor--) | 使用此属性管理 GIF 图像的背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 使用此属性管理 GIF 图像的背景颜色。 |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | 使用此属性控制 GIF 图像的背景颜色索引。 |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | 使用此属性控制 GIF 图像的背景颜色索引。 |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | 使用此属性管理 GIF 图像的像素宽高比。 |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | 使用此属性管理 GIF 图像的像素宽高比。 |
| [hasTransparentColor()](#hasTransparentColor--) | 确定 GIF 图像的活动帧是否包含透明颜色。 |
| [getTransparentColor()](#getTransparentColor--) | 检索 GIF 图像中活动帧的透明颜色。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 确定 GIF 图像的活动帧是否包含透明颜色。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 此属性决定 GIF 图像是否包含背景颜色。 |
| [getImageOpacity()](#getImageOpacity--) | 检索图像中活动帧的不透明度，提供其透明度水平的洞察。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整此 [Image](../../com.aspose.imaging/image) 实例的大小。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 调整此 [Image](../../com.aspose.imaging/image) 实例的大小。 |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | 在调整图像大小时考虑 GIF 中每页的完整帧，从而防止潜在伪影的出现。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 仅对活动帧执行旋转、翻转或两者兼施。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | 对当前图像应用抖动处理。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 使用指定的矩形区域裁剪图像。 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 通过应用伽马校正提升图像质量。 |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | 对图像的指定区域应用特定滤镜，以提升视觉质量或按需改变外观。 |
| [setFrameTime(int time)](#setFrameTime-int-) | 以毫秒为单位调整每帧的持续时间，确保整个图像序列的时间保持一致。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 根据指定的 `brightness` 参数调整图像的亮度。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 调整图像的对比度，增强或降低像素之间的亮度差异。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 图像的伽马校正对像素值进行非线性调整，根据红、绿、蓝通道的指定系数来增强或降低亮度。 |
| [grayscale()](#grayscale--) | 将图像转换为灰度表示会通过去除颜色信息而保留亮度，将彩色图像转换为灰度版本。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义阈值对图像进行二值化会将灰度或彩色图像转换为二值图像，根据像素强度值是否超过指定阈值，将每个像素分类为黑或白。 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值法对图像进行二值化是一种自动确定将灰度图像转换为二值图像的最佳阈值的方法。 |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | 使用 Bradley 自适应阈值算法结合积分图阈值进行图像二值化是一种将灰度图像转换为二值图像的方法。 |
| [orderBlocks()](#orderBlocks--) | 按照 GIF 规范对 GIF 块进行排序可确保 GIF 布局正确并符合标准。 |
| [clearBlocks()](#clearBlocks--) | 清除所有 GIF 块会删除图像中存储的任何现有数据。 |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | 插入新的 GIF 块允许您在图像的特定位置添加自定义数据。 |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | 添加新的 GIF 块可让您在图像中包含额外的数据。 |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | 移除 GIF 块会从图像中删除特定数据，提供清理或修改图像结构的能力。 |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | 等比例缩放在调整图像尺寸的同时保持宽高比，确保图像不会出现拉伸或失真。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | 此方法围绕图像中心点旋转图像。 |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// 创建一个 100x100 像素的 GIF 帧块。
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // 将整个块填充为红色。
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // 加载帧
    RasterImage[] frames = loadFrames("Animation frames");

    // 使用第一帧创建 GIF 图像
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // 使用 AddPage 方法向 GIF 图像添加帧
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // 保存 GIF 图像
        image.save("Multipage.gif");
    }

    // 释放资源
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


使用指定的首帧和全局调色板参数初始化一个新的 [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) 对象。快速开始管理 GIF 图像，确保通过可自定义设置实现准确呈现并获得最佳效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | 用于初始化 GIF 图像的第一帧。 |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要使用的全局调色板。注意，如果 `firstFrame` 和 `globalPalette` 均为 null，则使用默认全局调色板。 |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


使用 [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) 构造函数，制作 GIF 图像变得轻而易举。只需提供 firstFrame 参数，即可进入动态视觉交流的世界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | 用于初始化 GIF 图像的第一帧。 |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


使用 [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) 构造函数，轻松入门。通过此简便方法，您可以轻松创建动画 GIF。只需提供 firstFrame、globalPalette、paletteColorResolution、aspectRatio 等参数，即可让您的视觉作品栩栩如生。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | 用于初始化 GIF 图像的第一帧。 |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要使用的全局调色板。注意，如果 `firstFrame` 和 `globalPalette` 均为 null，则使用默认全局调色板。 |
| isPaletteSorted | boolean | 如果设置为 `true`，调色板将被排序。注意，当 `globalPalette` 不为 null 时使用此参数。 |
| paletteColorResolution | byte | 调色板颜色分辨率。注意，当 `globalPalette` 不为 null 时使用此参数。 |
| paletteBackgroundColorIndex | byte | 调色板背景颜色索引。 |
| aspectRatio | byte | 宽高比。 |
| hasTrailer | boolean | 如果设置为 `true`，GIF 图像将包含尾部；否则在流的末尾不写入尾部。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


通过此属性轻松获取文件格式。它是识别文件格式的首选来源。无缝集成到您的工作流中，提供关键信息，毫不费力。

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


使用此属性管理 GIF 文件中尾部的存在。无论是检查是否存在尾部还是设置其存在性，此属性都能简化操作。通过此直观功能保持 GIF 文件结构化和符合规范。

**Returns:**
boolean - `true` 表示 GIF 有尾部；否则为 `false`。
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


使用此属性管理 GIF 文件中尾部的存在。无论是检查是否存在尾部还是设置其存在性，此属性都能简化操作。通过此直观功能保持 GIF 文件结构化和符合规范。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | `true` 表示 GIF 有尾部；否则为 `false`。 |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


使用此属性控制 GIF 图像中调色板的排序。无论是检查调色板是否已排序还是设置排序行为，此属性都提供了管理 GIF 文件中调色板组织的简便方式。

**Returns:**
boolean - 如果调色板已排序则为 `true`；否则为 `false`。
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


使用此属性控制 GIF 图像中调色板的排序。无论是检查调色板是否已排序还是设置排序行为，此属性都提供了管理 GIF 文件中调色板组织的简便方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | `true` 表示调色板已排序；否则为 `false`。 |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


通过此属性轻松获取循环计数。如果您的 GIF 图像包含循环信息，此属性可快速访问循环计数，帮助您无缝管理 GIF 文件的循环行为。

**Returns:**
int - 循环计数或 1（默认值）
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


通过此属性轻松获取循环计数。如果您的 GIF 图像包含循环信息，此属性可快速访问循环计数，帮助您无缝管理 GIF 文件的循环行为。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 循环计数或 1（默认值） |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


使用此属性管理 GIF 图像的调色板颜色分辨率。调整调色板中表示颜色的位数，提供对色深和图像质量的精细控制。

**Returns:**
byte - 调色板颜色分辨率位数。
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


使用此属性管理 GIF 图像的调色板颜色分辨率。调整调色板中表示颜色的位数，提供对色深和图像质量的精细控制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 调色板颜色分辨率位数。 |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


通过此简洁属性获取图像中包含的总页数。非常适合快速评估图像内容的范围。

**Returns:**
int - 页数。
### getPages() {#getPages--}
```
public Image[] getPages()
```


通过此便利属性访问图像中的页面，允许根据需要无缝导航和操作各个页面。

**Returns:**
com.aspose.imaging.Image[] - 页面。
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


使用此属性无缝访问 GIF 块，便于轻松检索和操作图像的底层数据结构。

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - GIF 块。
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


确定图像是否为隔行扫描，这会影响加载时的显示。此属性提供对图像渲染行为的洞察，对于优化加载策略和提升整体观看体验至关重要。

**Returns:**
boolean - 如果此图像实例为隔行扫描，则为 `true`；否则为 `false`。
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


检索基于原始文件设置的选项，这对于在图像处理和操作中保持保真度和一致性至关重要。此方法允许将文件特定参数无缝集成到后续操作中，确保准确呈现并遵循图像的固有特性。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) 方法保存，它将生成每像素 8 位的输出 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) 方法。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


将新页面无缝合并到现有图像中，增强其内容并扩展其范围。此方法为图像集合添加额外内容，促进图像管理和构图的创造力与灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | 要添加的页面。 |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // 加载帧
    RasterImage[] frames = loadFrames("Animation frames");

    // 使用第一帧创建 GIF 图像
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // 使用 AddPage 方法向 GIF 图像添加帧
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // 保存 GIF 图像
        image.save("Multipage.gif");
    }

    // 释放资源
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


使用此属性管理和操作帧，实现对 GIF 图像中活动帧的平滑导航和修改。

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// 输出如下：
// 活动帧大小: { Width = 100, Height = 100}
// 清除所有块
// 未设置活动帧
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


使用此属性管理和操作帧，实现对 GIF 图像中活动帧的平滑导航和修改。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | 活动帧。 |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


使用此属性管理 GIF 图像的背景颜色。您可以设置或检索背景颜色，以确保一致性并提升视觉效果。

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


使用此属性管理 GIF 图像的背景颜色。您可以设置或检索背景颜色，以确保一致性并提升视觉效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 背景颜色。 |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


使用此属性控制 GIF 图像的背景颜色索引。设置或检索该索引，以保持一致性或实现所需的视觉效果。

**Returns:**
byte - 背景颜色索引。
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


使用此属性控制 GIF 图像的背景颜色索引。设置或检索该索引，以保持一致性或实现所需的视觉效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 背景颜色索引。 |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


使用此属性管理 GIF 图像的像素宽高比。设置或检索该比例，以确保准确渲染并保持视觉保真度。

**Returns:**
byte - 像素宽高比。
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


使用此属性管理 GIF 图像的像素宽高比。设置或检索该比例，以确保准确渲染并保持视觉保真度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 像素宽高比。 |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


确定 GIF 图像的活动帧是否包含透明颜色。此属性提供了一种便捷的方式来检查图像中的透明度。

**Returns:**
boolean - 表示活动帧是否具有透明颜色的值。
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


检索 GIF 图像中活动帧的透明颜色。此属性允许您访问当前活动帧中被指定为透明的特定颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


确定 GIF 图像的活动帧是否包含透明颜色。此属性提供了一种便捷的方式来检查图像中的透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 表示活动帧是否具有透明颜色的值。 |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


此属性决定 GIF 图像是否包含背景颜色。如果为 true，则表示图像包含背景颜色。

**Returns:**
boolean - 表示图像是否具有背景颜色的值。
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


检索图像中活动帧的不透明度，以了解其透明程度。此属性对于理解图像中活动帧的透明或不透明程度特别有用。

不透明度值介于 0.0（完全透明）和 1.0（完全不透明）之间。

**Returns:**
float - 此图像（活动帧）的不透明度。
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


调整此 [Image](../../com.aspose.imaging/image) 实例的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


调整此 [Image](../../com.aspose.imaging/image) 实例的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 设置。 |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// 基于加权和混合有理函数以及 lanczos3 插值的自适应算法。
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// 小矩形滤波器
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// 调色板中的颜色数量。
resizeSettings.setEntriesCount(256);

// 未使用颜色量化
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// 欧几里得方法
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 使用自适应重采样将尺寸缩小 2 倍。
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // 保存为 PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


在调整图像大小时考虑 GIF 中每页的完整帧，从而防止潜在的伪影出现。此方法对于保持图像的完整性和质量至关重要，尤其在处理动画 GIF 或帧序列时。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


仅对活动帧执行旋转、翻转或两者兼顾的操作。此操作仅对图像当前活动帧进行变换，保持序列中其他帧的完整性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// 下面主示例中使用的辅助类。
class Utils {
    // 获取文件格式字符串表示的辅助方法。
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// 以下是主要示例
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // 旋转、翻转并保存到输出文件。
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


对当前图像应用抖动处理。此过程通过降低颜色条纹并改善颜色过渡来提升图像质量，使外观更平滑。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 抖动的自定义调色板。 |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 使用包含 16 种颜色的 4 位色彩调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 使用仅包含 2 种颜色（黑色和白色）的 1 位色彩调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


使用指定的矩形区域裁剪图像。此操作会去除图像的外部部分，仅保留矩形定义的选定区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |


**Example: The following example crops a GIF image.**
下面的示例裁剪 GIF 图像。裁剪区域通过 Aspose.Imaging.Rectangle 指定。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 裁剪图像。裁剪区域是图像的中心矩形区域。
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // 将裁剪后的图像保存为 PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


通过应用伽马校正提升图像质量。此方法调整图像的颜色伽马以获得最佳视觉清晰度。它会修改每个像素的伽马值，从而改善颜色呈现和整体图像外观。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | float | 红色、绿色和蓝色通道的伽马系数 |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 为红色、绿色和蓝色通道设置伽马系数。
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


对图像指定区域应用特定滤镜，以提升视觉质量或按需改变外观。此方法在定义的矩形内有选择地处理像素，能够进行针对性调整，同时保持周围图像数据的完整性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | 选项。 |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 对整幅图像应用矩形大小为 5 的中值滤波器。
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 对整幅图像应用核大小为 5 的双边平滑滤波器。
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 对整幅图像应用半径为 5、sigma 值为 4.0 的高斯模糊滤波器。
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 对整幅图像应用核大小为 5、sigma 值为 4.0 的锐化滤波器。
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


以毫秒为单位调整每帧的持续时间，确保整个图像序列的时间一致。此方法统一设置每帧的显示时间，从而精确控制动画速度。更改此值将重置所有帧的延迟。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 时间 | int | 帧持续时间的毫秒数。 |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


根据指定的 `brightness` 参数调整图像的亮度。此方法统一修改整幅图像的亮度，增强或降低整体亮度以实现所需效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 设置亮度值。亮度的可接受范围为 [-255, 255]。
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


调整图像的对比度，增强或降低像素之间的亮度差异。此方法修改图像的整体色调范围，使暗部更暗、亮部更亮，以提升视觉清晰度和细节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | float | 对比度值（范围为 [-100; 100]） |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 设置对比度值。对比度的可接受范围为 [-100f, 100f]。
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


图像的伽马校正对像素值进行非线性调整，根据红、绿、蓝通道的指定系数来增强或降低亮度。此方法有助于微调图像的色彩平衡和亮度，提升整体外观和视觉质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | float | 红色通道的伽马系数 |
| gammaGreen | float | 绿色通道的伽马系数 |
| gammaBlue | float | 蓝色通道的伽马系数 |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 为红色、绿色和蓝色通道设置各自的伽马系数。
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


将图像转换为灰度表示会通过去除颜色信息而保留亮度，将彩色图像转为灰度版本。此过程将图像简化为灰色阴影，适用于打印、文档处理和灰度分析等多种应用。


**Example: The following example transforms a colored GIF image to its grayscale representation.**
下面的示例将彩色 GIF 图像转换为灰度表示。灰度图像仅由灰色阴影组成，仅携带强度信息。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


使用预定义阈值对图像进行二值化会将灰度或彩色图像转换为二值图像，根据像素强度值是否超过指定阈值，将每个像素分类为黑或白。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。若像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |


**Example: The following example binarizes a GIF image with the predefined threshold.**
下面的示例使用预定义阈值对 GIF 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为 255；否则为 0。
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


使用 Otsu 阈值的图像二值化是一种自动确定将灰度图像转换为二值图像的最佳阈值的方法。Otsu 阈值算法计算能够最小化两类（前景和背景）像素强度内部方差的阈值。当最佳阈值未知且需根据图像直方图自适应确定时，此技术尤为有用。


**Example: The following example binarizes a GIF image with Otsu thresholding.**
下面的示例使用 Otsu 阈值对 GIF 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 使用 Otsu 阈值法对图像进行二值化。
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


使用 Bradley 自适应阈值算法（结合积分图阈值）对图像进行二值化是一种将灰度图像转换为二值图像的方法。该算法根据指定窗口内周围像素的平均强度为每个像素计算局部阈值。通过基于局部像素强度自适应调整阈值，Bradley 方法能够有效处理图像中光照和对比度的变化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素与以该像素为中心的 s × s 窗口像素平均值之间的亮度差。 |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


按照 GIF 规范对 GIF 块进行排序可确保 GIF 布局正确并符合标准。此过程涉及按照规范定义的顺序排列块。此外，还可能需要移除某些对最终布局非必需的 [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) 实例。遵循 GIF 规范后，生成的图像将结构正确，兼容 GIF 查看应用程序。

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


清除所有 GIF 块会删除图像中存储的任何现有数据。此操作有效地将图像重置为空状态，去除之前添加的所有块。当需要以全新状态创建或修改 GIF 图像时，请使用此方法。


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// 输出如下：
// 活动帧大小: { Width = 100, Height = 100}
// 清除所有块
// 未设置活动帧
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


插入新的 GIF 块可让您在图像的特定位置添加自定义数据。此方法使您能够在 GIF 图像中将自定义块放置在所需位置，提供了组织和构建图像数据的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 零基索引的元素，即块将被插入的位置。 |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | 要添加的 GIF 块。 |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


添加新的 GIF 块可让您在图像中包含额外数据。此方法使您能够向 GIF 图像追加自定义块，这些块可以包含各种类型的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | 要添加的 GIF 块。 |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 GIF 图像。
// 默认情况下，第一个块是全黑的。
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // 第一个圆是红色的
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // 第二个圆是黑色的
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // 逐渐增加黑色弧形的角度并抹去红色弧形。
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


删除 GIF 块会从图像中移除特定数据，提供清理或修改图像结构的能力。此方法使您能够删除不需要或多余的块，从而优化 GIF 图像以实现高效存储。使用此功能可消除图像中过时的信息，同时保持其完整性和质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | 要移除的块。 |

--------------------

注意：如果您不会将该块添加到其他 GifImage，请不要忘记释放（Dispose）该块。 |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


比例缩放在调整图像尺寸的同时保持其宽高比，确保图像不会出现拉伸或变形。此方法按比例缩放图像，宽度和高度使用相同的因子进行缩放。比例缩放将根据 `newWidth`/width 和 `newHeight`/height 的比例来调整每一帧的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


此方法围绕图像中心点旋转图像。通过指定旋转角度，您可以顺时针或逆时针旋转图像，以实现所需的方向。此旋转有助于在不扭曲内容的情况下调整图像的呈现或对齐。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度，以度为单位。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅 `` 图像内容被旋转。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

