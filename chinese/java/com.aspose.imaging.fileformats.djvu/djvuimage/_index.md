---
title: "DjvuImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "DjVu 文档类支持图形文件格式，并促进对扫描文档和书籍的无缝管理，将文本、图纸、图像和照片集成到单一格式中。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

DjVu 文档类支持图形文件格式，并促进对扫描文档和书籍的无缝管理，将文本、图纸、图像和照片集成到单一格式中。支持多页操作，您可以高效地访问唯一文档标识符、统计页数、设置活动页以及检索特定文档页。该类提供调整大小、旋转、抖动、裁剪、灰度转换、伽马校正、调整和滤镜应用等功能，使您能够精确地操作和增强 DjVu 图像，以轻松且精准地满足各种应用需求。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | 通过使用 Stream 参数初始化 [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) 类的新实例，开始使用 DjVu 图像。 |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | 使用此构造函数无缝开始使用 DjVu 图像，它使用 Stream 和 LoadOptions 参数初始化 [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) 类的新实例。 |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | 使用此构造函数无缝开始使用 DjVu 图像，它使用 Stream 和 LoadOptions 参数初始化 [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | 当属性值更改时发生。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | 使用此方法加载您的 DjVu 文档。 |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | 加载文档。 |
| [getIdentifier()](#getIdentifier--) | 获取文档的唯一标识符 |
| [getPageCount()](#getPageCount--) | 使用此属性检索 DjVu 图像集合中的总页数。 |
| [getPages()](#getPages--) | 使用此属性访问 DjVu 图像集合中的各个页面。 |
| [getDjvuPages()](#getDjvuPages--) | 使用此属性快速检索 DjVu 文档中包含的所有页面。 |
| [getActivePage()](#getActivePage--) | 使用此属性访问或设置当前活动页面，以在 DjVu 文档中进行导航。 |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | 使用此属性访问或设置当前活动页面，以在 DjVu 文档中进行导航。 |
| [getFirstPage()](#getFirstPage--) | 使用此属性访问 DjVu 文档的第一页。 |
| [getLastPage()](#getLastPage--) | 使用此属性检索 DjVu 文档的最后一页。 |
| [getNextPage()](#getNextPage--) | 使用此便捷属性访问下一页，以在 DjVu 文档中进行导航。 |
| [getPreviousPage()](#getPreviousPage--) | 使用此便捷属性访问上一页，快速在 DjVu 文档的查看或处理任务中向后移动。 |
| [getFileFormat()](#getFileFormat--) | 获取与您的 DjVu 图像文件关联的文件格式信息。 |
| [hasAlpha()](#hasAlpha--) | 快速确定您的 DjVu 图像文件是否包含 alpha 通道。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | 使用 RasterCachedMultipageImage 类的 Rotate 方法围绕中心旋转图像。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 使用 \`Resize\` 方法调整图像大小，提供一种简单且有效的方式，根据您的需求调整图像的尺寸。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | \`ResizeWidthProportionally\` 方法提供了一种便捷的解决方案，在保持宽高比的同时调整图像的宽度。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | \`ResizeHeightProportionally\` 方法允许您在保持宽高比的同时调整图像的高度。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | \`RotateFlip\` 方法提供了多功能的图像操作选项，允许您对活动帧独立进行旋转、翻转或两者同时操作。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | \"Dither\" 函数对图像应用抖动效果，通过减少条纹并改善颜色过渡来提升视觉质量。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | "Crop" 修剪您的图像，以聚焦特定细节或去除不需要的元素，提升构图和视觉冲击力。 |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | 带位移的 Crop 允许您精确调整图像中裁剪区域的位置和尺寸。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义阈值的二值化将复杂图像简化为二进制表示，像素根据其强度相对于指定阈值的比较被归类为黑或白。 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值的二值化是一种基于图像直方图自动计算最佳阈值的技术。 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 自适应阈值算法结合积分图阈值的二值化是一种根据局部邻域为每个像素计算局部阈值的方法。 |
| [grayscale()](#grayscale--) | 灰度转换将图像转换为黑白表示，每个像素的强度以介于黑到白之间的单一数值表示。 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 伽马校正，特别针对红、绿、蓝通道，涉及分别调整每个颜色分量的亮度。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 对图像进行伽马校正时，可为红、绿、蓝通道自定义参数，从而实现颜色平衡和亮度的精确调节。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 使用指定参数调整图像的 `brightness`，提供对亮度水平的控制，以获得最佳视觉清晰度。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 使用此方法增强 [Image](../../com.aspose.imaging/image) 对比度，以提升视觉清晰度并突出细节，该方法调整明暗区域之间的亮度差异。 |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | 对图像中指定的矩形区域应用滤镜，以增强或修改其外观。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 在必要时应用其他设置，将图像调整为指定的宽度和高度。 |
| [cacheData()](#cacheData--) | 私有缓存数据以优化性能并减少对外部来源重复检索数据的需求。 |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // 将每页保存为单独的 PNG 图像。
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // 根据页码生成文件名。
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


通过使用 Stream 参数初始化 [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) 类的新实例，开始使用 DjVu 图像。非常适合希望在项目中无缝集成 DjVu 图像处理的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


使用此构造函数无缝开始处理 DjVu 图像，它使用 Stream 和 LoadOptions 参数初始化 [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) 类的新实例。非常适合希望在保持简洁高效的同时对 DjVu 图像加载选项进行精确控制的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 要加载的流。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


使用此构造函数无缝开始处理 DjVu 图像，它使用 Stream 和 LoadOptions 参数初始化 [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) 类的新实例。非常适合希望在保持简洁高效的同时对 DjVu 图像加载选项进行精确控制的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream | 要加载的流。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


当属性值更改时发生。

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


使用此方法加载您的 DjVu 文档。通过快速访问并导入 DjVu 文件到您的应用程序，简化工作流程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


加载文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


获取文档的唯一标识符

**Returns:**
int - 标识符。
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


使用此属性检索 DjVu 图像集合中的总页数。非常适合快速评估存储为 DjVu 格式的文档或书籍的规模。通过准确的页数信息提升工作流效率。

**Returns:**
int - 页数。
### getPages() {#getPages--}
```
public Image[] getPages()
```


使用此属性访问 DjVu 图像集合中的各个页面。通过直接访问每页，简化对存储为 DjVu 格式的文档或书籍的导航和操作。通过轻松的页面检索提升工作流效率。

**Returns:**
com.aspose.imaging.Image[] - 页面。

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // 将每页保存为单独的 PNG 图像。
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // 根据页码生成文件名。
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


使用此属性快速检索 DjVu 文档中包含的所有页面。通过轻松访问和管理 DjVu 文件中的各个页面，简化文档处理工作流。通过便捷的页面检索提升效率并优化任务流程。

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - 页面。
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


通过使用此属性访问或设置当前活动页来浏览您的 DjVu 文档。无缝切换页面以聚焦特定内容，提升文档查看体验。

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//输出可能如下所示：
//总页数：2
//当前页码：    1
//第一页页码：     1
//最后一页页码：      2
//--------------------------------------------------
//页码：     1
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
//--------------------------------------------------
//页码：     2
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


通过使用此属性访问或设置当前活动页来浏览您的 DjVu 文档。无缝切换页面以聚焦特定内容，提升文档查看体验。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | 活动页。 |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


使用此属性访问 DjVu 文档的首页。快速获取首页，以便高效开始查看或处理文档。

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//输出可能如下所示：
//总页数：2
//当前页码：    1
//第一页页码：     1
//最后一页页码：      2
//--------------------------------------------------
//页码：     1
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
//--------------------------------------------------
//页码：     2
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


使用此属性检索 DjVu 文档的最后一页。轻松快速访问末页，以便查看或处理。

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//输出可能如下所示：
//总页数：2
//当前页码：    1
//第一页页码：     1
//最后一页页码：      2
//--------------------------------------------------
//页码：     1
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
//--------------------------------------------------
//页码：     2
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


通过此便捷属性访问下一页来浏览 DjVu 文档。快速向前移动，进行文档查看或处理任务。

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


通过此便捷属性访问上一页，快速向后移动 DjVu 文档的查看或处理任务。轻松高效地在文档中导航。

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


获取与 DjVu 图像文件关联的文件格式信息。快速确定文件格式，以便无缝集成到工作流中。

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


快速判断 DjVu 图像文件是否包含 alpha 通道。通过检查图像中的透明信息简化工作流。

**Returns:**
布尔型 - 是否具有 alpha 通道。
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


使用 RasterCachedMultipageImage 类的 Rotate 方法围绕图像中心旋转。此便捷功能可轻松调整图像方向，同时保持中心位置，提升图像操作能力。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则，尺寸保持不变，仅 `` 图像内容被旋转。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


使用 \`Resize\` 方法调整图像大小，提供一种简单有效的方式根据需求调整图像尺寸。此多功能特性使您能够轻松将图像缩放至所需大小，提升其在各种平台和应用中的可用性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


\`ResizeWidthProportionally\` 方法提供了一种便捷的解决方案，可在保持宽高比的同时调整图像宽度。通过按比例调整宽度，确保图像在不同设备和屏幕尺寸下保持视觉美观和一致性，提升其在各种场景中的多用性和可用性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| resizeType | int | 调整的类型。 |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
此示例加载 DJVU 图像，并使用多种缩放方法按比例调整大小。仅指定宽度，高度会自动计算。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


\`ResizeHeightProportionally\` 方法允许在保持宽高比的同时调整图像高度。这样可确保图像比例不变，防止失真并保持视觉完整性。无论是为网页、移动应用还是印刷媒体优化图像，此方法都能确保图像在不同平台和设备上呈现最佳效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整的类型。 |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
此示例加载 DJVU 图像，并使用多种缩放方法按比例调整大小。仅指定高度，宽度会自动计算。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


\`RotateFlip\` 方法提供多样的图像操作选项，允许对活动帧独立进行旋转、翻转或两者兼施。无论是编辑照片、创建图形还是提升数字艺术，此方法都能对图像的方向和构图进行精确控制，轻松高效地实现创意构想。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
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
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


"Dither" 功能对图像应用抖动效果，通过降低条纹并改善颜色过渡提升视觉质量。无论是数字艺术、摄影还是平面设计项目，此特性为图像增添专业感，使其更平滑、更精致。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 抖动的自定义调色板。 |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 使用包含 16 种颜色的 4 位色彩调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸也越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 使用仅包含 2 种颜色（黑色和白色）的 1 位色彩调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸也越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


"Crop" 可裁剪图像以聚焦特定细节或去除不需要的元素，提升构图和视觉冲击力。无论是为社交媒体调整照片、制作网站横幅，还是设计印刷材料，此工具都能帮助您精准、清晰地优化图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |


**Example: The following example crops a DJVU image.**
以下示例对 DJVU 图像进行裁剪。裁剪区域通过 Aspose.Imaging.Rectangle 指定。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 裁剪图像。裁剪区域是图像的中心矩形区域。
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // 将裁剪后的图像保存为 PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


带位移的裁剪可让您精确调整图像中裁剪区域的位置和尺寸。此功能对于优化构图、对齐元素以及突出视觉焦点极为重要。通过在裁剪过程中加入位移，您可以轻松实现像素级精度，微调图像的框架。

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


使用预定义阈值的二值化将复杂图像简化为二进制表示，像素根据相对于指定阈值的强度被归类为黑或白。此技术常用于图像处理，以提升清晰度、简化分析，并为后续处理步骤（如光学字符识别（OCR））做好准备。通过应用固定阈值，您可以快速将灰度图像转换为二值形式，便于解释和提取有意义的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。若像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
以下示例使用预定义阈值对 DJVU 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为 255，否则为 0。
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


使用 Otsu 阈值化的二值化是一种基于图像直方图自动计算最优阈值的技术。它通过最小化类内方差将图像分为前景和背景。Otsu 方法广泛用于将图像分割为二进制形式，尤其在像素强度分布呈双峰或多峰时。此方法对目标检测、图像分割和特征提取等任务有益，因为前景与背景的准确划分至关重要。


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
以下示例使用 Otsu 阈值化对 DJVU 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 使用 Otsu 阈值法对图像进行二值化。
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


使用 Bradley 自适应阈值算法结合积分图阈值化的二值化是一种基于局部邻域为每个像素计算局部阈值的方法。它能够适应图像中光照的变化，适用于光照不均的图像。通过使用积分图计算阈值，可高效处理大范围邻域，适用于实时应用。此技术常用于文档处理、OCR（光学字符识别）和图像分割任务，因为后续分析需要准确的二值化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素的亮度差是该像素与以其为中心的 s × s 窗口像素平均值之间的差异。 |
| windowSize | int | 以该像素为中心的 s × s 窗口的大小 |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
以下示例使用 Bradley 的自适应阈值算法对 DJVU 图像进行二值化，使用指定的窗口大小。二值化图像仅包含 2 种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 使用亮度差 5 对图像进行二值化。亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


灰度转换将图像转换为黑白表示，其中每个像素的强度由介于黑到白之间的单一数值表示。此过程去除颜色信息，生成单色图像。灰度图像常用于颜色非必需或追求简洁的场景，例如文档扫描、打印以及某些图像分析。


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
以下示例将彩色 DJVU 图像转换为其灰度表示。灰度图像仅由灰色阴影组成，仅携带强度信息。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


伽马校正（针对红、绿、蓝通道）涉及分别调整每个颜色分量的亮度。通过对 RGB 通道应用不同的伽马系数，可以微调图像的整体亮度和对比度。此技术确保颜色表现准确，并提升图像在不同显示设备上的视觉质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | float | 红色、绿色和蓝色通道系数的 Gamma |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 为红色、绿色和蓝色通道设置 Gamma 系数。
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


对图像进行伽马校正时，可为红、绿、蓝通道设置可自定义的参数，从而实现对色彩平衡和亮度的精确调节。该方法通过微调颜色表现提升图像质量，确保在不同显示设备上的最佳渲染。对各通道的伽马值进行调整可改善色彩平衡和视觉吸引力。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | float | 红色通道的伽马系数 |
| gammaGreen | float | 绿色通道的伽马系数 |
| gammaBlue | float | 蓝色通道系数的 Gamma |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 为红色、绿色和蓝色通道设置各自的 Gamma 系数。
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


使用指定参数调整图像的 `brightness`，以控制亮度水平，实现最佳视觉清晰度。此方法可增强或降低图像的整体亮度，允许进行细微调节以获得所需的光照效果。通过调节亮度，用户可以优化图像可见性并提升细节再现，从而获得更好的观看体验。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 设置亮度值。亮度的可接受范围为 [-255, 255]。
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


使用此方法提升 [Image](../../com.aspose.imaging/image) 对比度，以改善视觉清晰度并突出细节，该方法调整亮部与暗部之间的亮度差异。通过微调对比度水平，用户可以获得更鲜活、更有冲击力的图像，提升整体图像质量并最大化细节可见度。此调整有助于显现颜色和纹理的微妙差别，产生更具动感和视觉吸引力的图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | float | 对比度值（范围为 [-100; 100]） |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 设置对比度值。对比度的可接受范围为 [-100f, 100f]。
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


在图像的指定矩形区域内应用滤镜，以增强或修改其外观。通过针对特定区域，该方法可进行精确调节，如模糊、锐化或应用艺术效果，以实现期望的视觉效果。对选定区域的滤镜进行微调，使用户能够自定义图像美感、提升清晰度，并创建符合个人偏好的艺术效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | 选项。 |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 对整幅图像应用矩形大小为5的中值滤波器。
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 对整幅图像应用核大小为5的双边平滑滤波器。
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 对整幅图像应用半径为5、sigma值为4.0的高斯模糊滤波器。
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 对整幅图像应用半径为5、平滑值为4.0的Gauss-Wiener滤波器。
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 对整幅图像应用长度为5、平滑值为4.0、角度为90.0度的运动Wiener滤波器。
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 对整幅图像应用核大小为5、sigma值为4.0的锐化滤波器。
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


将图像调整为指定的宽度和高度，并根据需要应用其他设置。此方法使用户能够在保持所需属性（如宽高比、图像质量和压缩设置）的同时调整图像尺寸。通过提供灵活的缩放选项，用户可以根据特定需求定制图像，并优化其在各种应用和平台上的呈现效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 调整大小的设置。 |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 使用自适应重采样将尺寸缩小 2 倍。
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // 保存为 PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


私有缓存数据以优化性能，减少对外部来源的重复数据检索。此方法还能节约资源，尤其在数据访问频繁或资源受限的场景中。


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// 从 DJVU 文件加载图像。
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // 此调用会缓存所有页面，因而不会再从底层数据流中加载额外数据。
    image.cacheData();

    // 或者您可以单独缓存页面。
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

