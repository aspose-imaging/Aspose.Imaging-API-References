---
title: "DicomImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "此类实现了医学数字成像与通信（DICOM）光栅图像格式的支持，并提供了一个用于精确且灵活处理 DICOM 图像的综合解决方案。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

此类实现了医学数字成像与通信（DICOM）光栅图像格式的支持，并提供了一个用于精确且灵活处理 DICOM 图像的综合解决方案。您可以无缝操作图像页面，包括获取、添加或删除页面，以及控制默认页面和活动页面。它具备处理 Alpha 通道、嵌入 XMP 元数据、调整大小、旋转、裁剪、二值化、调节、应用滤镜以及转换为其他光栅格式的能力。此 API 使开发者能够有效处理 DICOM 图像，并满足医学成像领域中多样化的应用需求。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | 使用此构造函数并提供 dicomOptions 参数，轻松初始化 DicomImage 类的全新实例。 |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | 在此构造函数中使用流和 loadOptions 参数，平稳地创建 DicomImage 类的新实例。 |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | 通过在此构造函数中使用流参数，创建 DicomImage 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageCount()](#getPageCount--) | 使用此直观属性，获取图像的总页数。 |
| [getPages()](#getPages--) | 使用此直观属性访问图像的页面。 |
| [getFileInfo()](#getFileInfo--) | 使用此直观属性轻松获取 DICOM 文件的有价值的头信息。 |
| [getDicomPages()](#getDicomPages--) | 使用此直观属性访问图像的页面。 |
| [getActivePage()](#getActivePage--) | 使用此直观属性访问图像的活动页面。 |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | 使用此直观属性管理图像的活动页面。 |
| [getActivePageIndex()](#getActivePageIndex--) | 使用此直观属性轻松获取活动页面的索引。 |
| [getFileFormat()](#getFileFormat--) | 使用此直观属性轻松获取文件格式值。 |
| [hasAlpha()](#hasAlpha--) | 使用此直观属性轻松获取图像是否具有 Alpha 通道。 |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | 使用此直观方法通过添加新页面来扩展您的图像集合。 |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | 通过将对象的数据保存到指定的文件（索引器 + 文件名）位置，并使用指定的文件格式和选项，来保留对象的数据。 |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | 使用此简便方法精确调整此 [RasterImage](../../com.aspose.imaging/rasterimage) 的分辨率。 |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | 使用此便捷方法在保持宽高比的同时调整图像大小。 |
| [addPage()](#addPage--) | 使用此简便方法在图像页面列表末尾追加新页面。 |
| [insertPage(int pageIndex)](#insertPage-int-) | 使用此直观方法在指定索引处向图像页面列表插入新页面。 |
| [removePage(int pageIndex)](#removePage-int-) | 使用此便捷方法从页面列表中删除指定索引的页面。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | 使用此便捷方法围绕中心旋转图像。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 使用此简便方法调整图像的大小。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 使用此便捷方法在保持宽高比的同时调整图像的宽度。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 使用此用户友好方法在保持宽高比的同时调整图像的高度。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 使用此简便方法轻松通过旋转、翻转或同时执行两者来操作活动帧。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | 使用此简便方法通过应用抖动效果来增强当前图像。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 使用此简易方法裁剪图像，去除不需要的区域并聚焦关键内容。 |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | 使用此多功能方法通过平移来调整图像的裁剪区域。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用此简便方法通过预定义阈值轻松将图像转换为二进制格式。 |
| [binarizeOtsu()](#binarizeOtsu--) | 应用 Otsu 阈值化对图像进行二值化，自动根据图像直方图确定最佳阈值。 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 的自适应阈值算法对图像进行二值化，利用积分图阈值化提升性能。 |
| [grayscale()](#grayscale--) | 轻松将图像转换为灰度表示，简化视觉分析和处理任务。 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 使用伽马校正提升图像质量并进行调整，这是一种用于微调视觉外观的强大技术。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 通过对图像的红、绿、蓝分量分别进行伽马校正，实现精确的颜色调整。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 通过调整 `brightness` 来增强图像亮度，这是一种参数化方法，允许开发者细致调节图像的光度。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 使用此用户友好方法增强 [Image](../../com.aspose.imaging/image) 对比度，该方法调整明暗区域之间的差异。 |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | 通过对指定矩形区域应用滤镜，轻松增强图像的特定区域。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 使用此简易的重新缩放方法调整图像大小。 |
| [cacheData()](#cacheData--) | 此方法高效缓存数据，优化性能并确保在需要时快速访问。 |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// 加载图像
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // 使用矢量图形绘制内容。
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // 保存绘制图像的像素。它们现在位于 Dicom 图像的第一页。
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // 在后面添加几页，使其更暗。
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // 在主页前面添加几页，使其更亮。
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // 将创建的多页图像保存到输出文件。
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


使用此构造函数轻松初始化 DicomImage 类的新实例，利用 dicomOptions 参数。非常适合希望在项目中快速高效使用 [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) 对象的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | 该 dicom 选项（现在忽略）。 |
| width | int | 宽度。 |
| height | int | 高度。 |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


在此构造函数中使用流和 loadOptions 参数，顺畅地创建 DicomImage 类的新实例。非常适合渴望在项目中快速有效地使用 [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) 对象的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


通过在此构造函数中使用流参数，创建 DicomImage 类的新实例。非常适合希望在项目中从现有数据流初始化 [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) 对象的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


使用此直观属性获取图像的总页数。非常适合需要快速访问图像页数以确保高效导航和管理的开发者。

**Returns:**
int - 页数。
### getPages() {#getPages--}
```
public Image[] getPages()
```


使用此直观属性访问图像的各页。非常适合希望与图像中的单个页面交互，以确保流畅导航和操作的开发者。

**Returns:**
com.aspose.imaging.Image[] - 页面。
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


使用此直观属性轻松检索 DICOM 文件中的有价值头信息。非常适合希望快速访问 DICOM 文件中封装的关键细节的开发者，确保高效的数据提取和分析。

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


使用此直观属性访问图像的各页。非常适合希望与图像中的单个页面交互，以确保流畅导航和操作的开发者。

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] - 页面。
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


使用此直观属性访问图像的活动页。非常适合希望在多页图像中动态切换页面的开发者，确保高效的导航和处理。

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


使用此直观属性管理图像的活动页。非常适合希望在多页图像中动态切换页面的开发者，确保高效的导航和处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | 活动页。 |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


使用此直观属性轻松获取活动页的索引。非常适合希望快速访问多页图像中当前页索引的开发者，确保高效的导航和处理。

**Returns:**
int - 活动页的索引。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此直观属性轻松获取文件格式值。非常适合希望快速获取图像文件格式的开发者，确保根据文件类型进行高效的处理。

**Returns:**
long - 文件格式的值 [FileFormat](../../com.aspose.imaging/fileformat)。
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


使用此直观属性轻松获取图像是否具有 alpha 通道。非常适合希望确定图像是否包含透明信息的开发者，确保在图像处理任务中精确处理 alpha 通道数据。

**Returns:**
boolean - 如果图像具有 alpha 通道则为 true。
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


使用此直观方法通过添加新页面来扩展图像集合。非常适合希望动态向多页图像追加页面的开发者，确保图像内容的无缝扩展和组织。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | 要添加的页面。 |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


通过将对象的数据保存到指定文件（indexer + filename）位置并使用指定的文件格式和选项来保留数据。非常适合希望在保持灵活性和对保存参数的控制的同时安全地以多种格式存储数据的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | 选项。 |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


使用此简洁方法精确调整此 [RasterImage](../../com.aspose.imaging/rasterimage) 的分辨率。非常适合希望根据特定需求定制图像分辨率的开发者，确保最佳的显示质量和文件大小管理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | double | 水平分辨率（每英寸点数），对应于 [RasterImage](../../com.aspose.imaging/rasterimage)。 |
| dpiY | double | 垂直分辨率（每英寸点数），对应于 [RasterImage](../../com.aspose.imaging/rasterimage)。 |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


使用此便捷方法在保持宽高比的同时调整图像大小。非常适合希望按比例调整图像尺寸的开发者，确保一致性并保留原始内容的比例。比例缩放将根据 `newWidth`/width 和 `newHeight`/height 的比例对每帧进行大小调整。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


使用此简洁方法在图像页面列表末尾追加新页面。非常适合希望动态扩展多页图像的开发者，确保图像内容的无缝集成和组织。

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


使用此直观方法在指定索引处向图像页面列表插入新页面。非常适合希望对多页图像页面排列进行精确控制的开发者，确保图像内容的无缝组织和自定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | int | 页面的索引。 |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // 使用矢量图形绘制内容。
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // 保存绘制图像的像素。它们现在位于 Dicom 图像的第一页。
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // 在后面添加几页，使其更暗。
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // 在主页前面添加几页，使其更亮。
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // 将创建的多页图像保存到输出文件。
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


使用此便捷方法从页面列表中删除指定索引处的页面。非常适合希望对多页图像管理进行精确控制的开发者，确保图像内容的无缝组织和自定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | int | 页面的索引。 |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


使用此便捷方法围绕图像中心旋转图像。非常适合希望动态调整图像方向的开发者，确保在应用程序中实现最佳的展示和对齐。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（单位：度）。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则，尺寸保持不变，仅 `` 图像内容被旋转。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DICOM 图像。
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // 将图像围绕中心顺时针旋转 60 度。
        // 使用灰色作为背景颜色。
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // 注意，如果图像是彩色的，它将根据以下选项自动转换为灰度格式。
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // 创建一个 TIFF 帧数组。
        // 帧的数量等于 DJVU 页面的数量。
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // 将每页保存为单独的 TIFF 帧。
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // 基于 DICOM 页面创建一个 TIFF 帧。
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // 从这些帧合成一个 TIFF 图像。
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // 保存到文件。
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


使用此简便方法调整图像大小。非常适合希望动态调整图像尺寸的开发者，确保图像在其应用程序的各种场景和布局中无缝适配。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


使用此便捷方法在保持宽高比的同时调整图像宽度。非常适合希望按比例调整图像大小的开发者，确保在不同显示环境中获得一致且视觉上令人满意的效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| resizeType | int | 调整的类型。 |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
本示例加载 DICOM 图像并使用多种缩放方法按比例调整大小。仅指定宽度，高度会自动计算。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


使用此用户友好方法在保持宽高比的同时调整图像高度。非常适合希望动态调整图像大小并保持比例的开发者，确保在其应用程序中实现最佳显示和可用性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整的类型。 |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
本示例加载 DICOM 图像并使用多种缩放方法按比例调整大小。仅指定高度，宽度会自动计算。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


使用此简便方法轻松通过旋转、翻转或同时执行两者来操作活动帧。非常适合需要在图像序列中动态调整特定帧方向的开发者，确保最佳展示和对齐。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

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
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


使用此简便方法通过抖动效果增强当前图像。非常适合希望为图像添加纹理和深度、提升视觉质量和整体吸引力的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 抖动的自定义调色板。 |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 使用包含 16 种颜色的 4 位色彩调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸也越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 使用仅包含 2 种颜色（黑色和白色）的 1 位色彩调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸也越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


使用此简单方法裁剪图像，去除不需要的区域并聚焦关键内容。非常适合希望自定义图像视觉构图、确保有效传达预期信息的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |


**Example: The following example crops a DICOM image.**
以下示例裁剪 DICOM 图像。裁剪区域通过 Aspose.Imaging.Rectangle 指定。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 裁剪图像。裁剪区域是图像的中心矩形区域。
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // 将裁剪后的图像保存为 PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


使用此多功能方法通过平移来调整图像的裁剪区域。非常适合需要对裁剪过程进行精确控制、在保留重要细节的同时去除不必要元素的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | int | 左位移。 |
| rightShift | int | 右位移。 |
| topShift | int | 上位移。 |
| bottomShift | int | 下位移。 |


**Example: The following example crops a DICOM image.**
以下示例裁剪 DICOM 图像。裁剪区域通过左、上、右、下边距指定。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 再次裁剪。设置图像尺寸的 10% 边距。
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // 将裁剪后的图像保存为 PNG。
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


使用此简便方法通过预定义阈值轻松将图像转换为二值格式。非常适合希望通过基于指定强度水平将图像分割为前景和背景组件来简化图像处理任务的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。若像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
以下示例使用预定义阈值对 DICOM 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为 255，否则为 0。
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


应用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳阈值。非常适合希望以最少人工干预将图像分割为前景和背景区域的开发者。


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
以下示例使用 Otsu 阈值法对 DICOM 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 使用 Otsu 阈值法对图像进行二值化。
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


使用 Bradley 的自适应阈值算法对图像进行二值化，利用积分图阈值提升性能。非常适合希望基于局部亮度变化自动分割图像、在不同光照条件下确保准确目标检测和提取的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素的亮度差是该像素与以其为中心的 s × s 窗口像素平均值之间的差异。 |
| windowSize | int | 以该像素为中心的 s × s 窗口的大小 |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
以下示例使用指定窗口大小的 Bradley 自适应阈值算法对 DICOM 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 使用亮度差 5 对图像进行二值化。亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


使用此简便方法轻松将图像转换为灰度表示，简化视觉分析和处理任务。非常适合希望提升图像清晰度、降低复杂度并在各种应用中促进高效灰度算法的开发者。


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
以下示例将彩色 DICOM 图像转换为其灰度表示。灰度图像仅由灰色阴影组成，仅携带强度信息。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


通过伽马校正增强图像质量并进行调整，这是一种用于微调视觉外观的强大技术。非常适合希望优化图像呈现、调整色彩平衡并确保在不同设备和环境中保持一致渲染的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | float | 红色、绿色和蓝色通道系数的 Gamma |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 为红色、绿色和蓝色通道设置 Gamma 系数。
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


通过对图像的红、绿、蓝分量分别应用伽马校正，实现精确的颜色调整。此方法确保准确的色彩平衡和最佳的视觉输出，满足寻求对图像渲染和颜色精度进行细粒度控制的开发者需求。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | float | 红色通道的伽马系数 |
| gammaGreen | float | 绿色通道的伽马系数 |
| gammaBlue | float | 蓝色通道系数的 Gamma |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 为红色、绿色和蓝色通道设置各自的 Gamma 系数。
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


通过调整 `brightness` 参数来增强图像亮度，这是一种允许开发者细致调节图像光度的参数化方法。此用户友好函数使开发者能够无缝操作图像亮度，提供灵活性和对视觉美感的控制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 设置亮度值。亮度的可接受范围为 [-255, 255]。
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


使用此用户友好方法增强 [Image](../../com.aspose.imaging/image) 对比度，该方法调整明暗区域之间的差异。轻松提升视觉清晰度和定义度，为开发者提供直观的图像对比度控制，以实现最佳渲染。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | float | 对比度值（范围为 [-100; 100]） |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 设置对比度值。对比度的可接受范围为 [-100f, 100f]。
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


通过对指定矩形区域应用滤镜，轻松增强图像的特定区域。此方法为开发者提供对图像操作的精确控制，允许有针对性的调整，以轻松实现所需的视觉效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | 选项。 |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 对整幅图像应用矩形大小为5的中值滤波器。
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 对整幅图像应用核大小为5的双边平滑滤波器。
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 对整幅图像应用半径为5、sigma值为4.0的高斯模糊滤波器。
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 对整幅图像应用半径为5、平滑值为4.0的Gauss-Wiener滤波器。
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 对整幅图像应用长度为5、平滑值为4.0、角度为90.0度的运动Wiener滤波器。
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 对整幅图像应用核大小为5、sigma值为4.0的锐化滤波器。
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


使用此简易的尺寸调整方法改变图像大小。无论是需要缩小还是放大图像，此功能都能高效、准确地满足您的尺寸调整需求，非常适合寻求快速简便图像尺寸修改的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 调整大小的设置。 |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 使用自适应重采样将尺寸缩小 2 倍。
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // 保存为 PNG
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


此方法高效缓存数据，优化性能并确保在需要时快速访问。是希望通过智能管理数据资源来提升应用程序速度和效率的开发者的理想选择。


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// 从 DICOM 文件加载图像。
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // 此调用会缓存所有页面，因而不会再从底层数据流中加载额外数据。
    image.cacheData();

    // 或者您可以单独缓存页面。
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

