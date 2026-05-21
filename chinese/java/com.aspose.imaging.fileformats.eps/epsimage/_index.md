---
title: "EpsImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "用于封装PostScript（EPS）图像文件格式支持的 API 提供了强大的功能，可操作包含文本、图形和图像的组合。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

用于封装PostScript（EPS）图像文件格式支持的 API 提供了强大的功能，可操作包含文本、图形和图像的组合。它具备位图预览图像处理、方向翻转、获取插图边界的边界框、调整大小、旋转图像以及添加预览图像等特性。该 API 确保以精确且多功能的方式无缝处理和集成 EPS 文件到各种应用程序中。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | 轻松获取可用的预览图像数量。 |
| [getPreviewImages()](#getPreviewImages--) | 检索与您的文件关联的预览图像。 |
| [getFileFormat()](#getFileFormat--) | 使用此属性访问图像的文件格式。 |
| [getEpsType()](#getEpsType--) | 访问并解释 EPS 图像的子类型值，以简化工作流并提升跨平台兼容性。 |
| [hasRasterPreview()](#hasRasterPreview--) | 通过此属性轻松发现光栅预览的存在。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 使用此属性轻松获取图像的精确位深。 |
| [getWidthF()](#getWidthF--) | 使用此便捷属性检索图像的宽度。 |
| [getHeightF()](#getHeightF--) | 使用此属性访问图像的高度。 |
| [isCached()](#isCached--) | 此属性提供了一种便捷方式来检查对象的数据是否已缓存，从而消除额外读取数据的需求。 |
| [getPsStream()](#getPsStream--) | 获取包含要执行的 PostScript 的流。 |
| [getPostScriptVersion()](#getPostScriptVersion--) | 此属性检索与 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例关联的 PostScript 版本。 |
| [getTitle()](#getTitle--) | 此属性检索从 EPS 文件中嵌入的 EPS 文档结构约定（DSC）注释中提取的标题。 |
| [getCreator()](#getCreator--) | 此属性提供对 EPS 文件中 EPS 文档结构约定（DSC）注释中获取的创建者信息的访问。 |
| [getCreationDate()](#getCreationDate--) | 此属性从 EPS 文档结构约定（DSC）注释中检索创建日期，提供指示 EPS 文件创建时间的关键元数据。 |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | 此属性从 EPS 文档结构约定（DSC）注释中检索创建日期，提供指示 EPS 文件创建时间的关键元数据。 |
| [getBoundingBox()](#getBoundingBox--) | 通过访问以设备无关点表示的原始边界框，此属性提供有关 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 尺寸的关键几何信息。 |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | 此属性以像素返回 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例的原始边界框，提供用于精确渲染和操作的关键几何数据。 |
| [cacheData()](#cacheData--) | 此属性以像素返回 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例的原始边界框，提供用于精确渲染和操作的关键几何数据。 |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | 访问链接到 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例的预览图像，便于在应用程序中无缝检索以进行检查或使用。 |
| [getPreviewImage()](#getPreviewImage--) | 检索指定 `format` 的现有预览图像，如果未找到则返回 ``。 |
| [getPreviewImage(long format)](#getPreviewImage-long-) | 检索指定 `format` 的现有预览图像，如果未找到则返回 ``。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 自定义图像调色板以实现独特的配色方案并提升视觉吸引力。 |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// 加载 EPS 图像
try (Image image = Image.load("AstrixObelix.eps"))
{
    // 使用 Mitchell 三次插值方法调整图像大小
    image.resize(400, 400, ResizeType.Mitchell);

    // 将图像导出为 PNG 格式
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// 加载 EPS 图像
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // 设置插值模式
    resizeSettings.setMode(ResizeType.LanczosResample);
    // 设置过滤器的类型
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // 设置颜色比较方法
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // 设置颜色量化方法
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // 使用高级调整设置调整图像大小
    image.resize(400, 400, resizeSettings);

    // 将图像导出为 PNG 格式
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


轻松获取可用的预览图像数量。此属性让您能够轻松检索与文件关联的预览图像计数，从而实现对图像预览的高效管理和导航。非常适合优化工作流并有效组织图像资产。

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


检索与您的文件关联的预览图像。此属性提供对预览图像集合的无缝访问，使您能够根据需要高效浏览和管理它们。非常适合快速预览并为项目选择合适的图像。

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此属性访问图像的文件格式。检索有关图像文件格式的关键信息，以促进兼容性和高效处理。非常适合识别图像文件格式，以实现无缝集成到您的项目中。

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


访问并解释您的 EPS 图像的子类型值，简化工作流并提升跨平台兼容性。非常适合在项目中以精确高效的方式优化 EPS 子类型的检索。

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


使用此属性轻松发现光栅预览的存在。获取布尔值以指示 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例是否包含光栅预览，为您的图像处理任务提供清晰高效的支持。非常适合根据 EPS 图像中光栅预览的有无来简化工作流决策。

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


使用此属性轻松获取图像的精确位深。检索每像素位数，提供有关图像颜色深度的关键信息，并帮助优化处理任务。非常适用于需要对图像操作和分析进行细粒度控制的应用程序。

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


使用此便捷属性获取图像的宽度。轻松获取图像宽度，便于在应用程序中进行精确的布局计算、缩放操作和尺寸相关任务。非常适合确保在各种平台和设备上准确渲染和显示图像。

**Returns:**
float - 图像宽度（像素）。
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


使用此属性访问图像的高度。轻松获取图像高度，实现无缝的布局调整、宽高比计算以及在不同屏幕分辨率和显示环境下的精确渲染。

**Returns:**
float - 图像高度（像素）。
### isCached() {#isCached--}
```
public boolean isCached()
```


此属性提供了一种便捷方式来检查对象的数据是否已缓存，省去额外读取数据的需求。它提供快速高效的方法来判断所需信息是否已随时可用，从而优化性能并降低数据密集型操作的资源开销。

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


获取包含要执行的 PostScript 的流。

**Returns:**
java.io.InputStream - 包含待执行 PostScript 的流。
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


此属性检索与 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例关联的 PostScript 版本。它提供对 EPS 文件中使用的特定 PostScript 语言版本的洞察，有助于兼容性评估并促进与支持 PostScript 的环境的无缝集成。

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


此属性检索从 EPS 文件中嵌入的 EPS 文档结构约定（DSC）注释中提取的标题。它提供有关 EPS 文件内容的有价值元数据，有助于在兼容的软件应用中进行文档组织和识别。

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


此属性提供对从 EPS 文件中 EPS 文档结构约定（DSC）注释获取的创建者信息的访问。了解创建者细节可洞察生成 EPS 文件所使用的软件或工具，帮助在各种平台和应用中进行兼容性评估。

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


从 EPS 文档结构约定（DSC）注释中检索创建日期，此属性提供指示 EPS 文件起始时间的关键元数据。通过访问这些信息，用户可了解文件的来源和时间顺序，提升文件管理和组织能力。

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


从 EPS 文档结构约定（DSC）注释中检索创建日期，此属性提供指示 EPS 文件起始时间的关键元数据。通过访问这些信息，用户可了解文件的来源和时间顺序，提升文件管理和组织能力。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


以设备无关点访问原始边界框，此属性提供关于 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 尺寸的关键几何信息。检索这些数据后，用户可准确评估图像的大小和宽高比，便于在各种应用中实现精确的布局和定位。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


此属性以像素返回 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例的原始边界框，提供用于精确渲染和操作的关键几何数据。凭借这些信息，用户可确保在项目中对 EPS 图像进行精确的放置和尺寸调整，提升整体视觉呈现和质量。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


此属性以像素返回 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例的原始边界框，提供用于精确渲染和操作的关键几何数据。凭借这些信息，用户可确保在项目中对 EPS 图像进行精确的放置和尺寸调整，提升整体视觉呈现和质量。

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


访问链接到 [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) 实例的预览图像，允许在应用中无缝检索以供检查或使用。此方法提供便捷的预览图像访问，提升用户与图像数据的交互体验。

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - 预览图像。
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


检索指定 `format` 的现有预览图像，如果未找到则返回 ``。此方法在访问特定格式的预览图像时提供灵活性，优化应用中的兼容性和资源管理。

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


检索指定 `format` 的现有预览图像，如果未找到则返回 ``。此方法在访问特定格式的预览图像时提供灵活性，优化应用中的兼容性和资源管理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | long | EPS 预览图像格式。 |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


自定义图像调色板以实现独特的配色方案并提升视觉吸引力。针对特定效果调整颜色，并轻松在不同平台和设备上优化图像质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

