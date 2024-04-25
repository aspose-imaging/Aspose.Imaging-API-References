---
title: EpsImage
second_title: Aspose.Imaging for .NET API 参考
description: EPS 格式的基类
type: docs
weight: 6560
url: /zh/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

EPS 格式的基类

```csharp
public abstract class EpsImage : VectorImage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | 获取每像素计数的图像位数。 |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | 获取边界框左下位置 |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | 获取BoundingBox 字符串值 |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | 获取边界框右上角位置 |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container) { get; } | 获取[`Image`](../../aspose.imaging/image)容器. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | 获取 CreationDate 字段 |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | 获取他的 CreationDate 字段字符串值 |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | 获取创建者字段 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| abstract [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype) { get; } | 获取 EPS 子类型值 |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | 获取或设置图像是否有背景色的值。 |
| abstract [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview) { get; } | 获取一个值，该值指示此实例是否具有特定于格式的光栅预览 |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | 获取对象高度，以英寸为单位。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | 获取一个值，表示对象的数据当前是否被缓存，不需要读取数据。 |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | 获取页码 |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | 获取页数 |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | 获取 Photoshop 预览缩略图（如果它存在于初始 EPS 数据中） |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | 获取 PostScript 版本字段 |
| [Size](../../aspose.imaging/image/size) { get; } | 获取图像大小。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | 获取对象大小，以英寸为单位。 |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | 获取标题字段 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | 获取指示是否使用图像调色板的值。 |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | 获取对象宽度，以英寸为单位。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | 缓存无法使用。 |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | 判断图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | 获取默认选项。 |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | 获取嵌入的图像。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存它[`Save`](../../aspose.imaging/datastreamsupporter/save)方法，将产生每像素8位的输出PNG图像。 为了避免它并以每像素1位保存PNG图像，使用此方法获取相应的保存选项并将它们 传递给[`Save`](../../aspose.imaging/image/save)方法作为第二个参数。 |
| [Resize](../../aspose.imaging/image/resize)(int, int) | 调整图像大小。默认NearestNeighbourResample已使用。 |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | 按比例调整高度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | 按比例调整宽度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | 按比例调整宽度。 |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | 旋转、翻转或旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流中。 |
| override [Save](../../aspose.imaging/image/save)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | 设置图像调色板。 |

### 例子

调整 EPS 图像大小并将其导出为 PNG 格式。

```csharp
[C#]

// 加载 EPS 图像
using (var image = Image.Load("AstrixObelix.eps"))
{
    // 使用米切尔三次插值法调整图像大小
    image.Resize(400, 400, ResizeType.Mitchell);

    // 将图片导出为PNG格式
    image.Save("ExportResult.png", new PngOptions());
}
```

使用 PostScript 渲染将 EPS 图像转换为 PDF。

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // 设置所需的 PDF 合规性
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

使用 PostScript 渲染将 EPS 图像转换为 PNG。

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PngOptions
    {
        VectorRasterizationOptions = new EpsRasterizationOptions
        {
            PageWidth = 500, // 图像宽度
            PageHeight = 500 // 图像高度
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // 使用 PostScript 渲染光栅图像
        }
    };

    image.Save("Sample.png", options);
}
```

使用高级设置调整 EPS 图像的大小。

```csharp
[C#]

// 加载 EPS 图像
using (var image = Image.Load("AstrixObelix.eps"))
{
    // 使用高级调整大小设置调整图像大小
    image.Resize(400, 400, new ImageResizeSettings
    {
        // 设置插值模式
        Mode = ResizeType.LanczosResample,

        // 设置过滤器的类型
        FilterType = ImageFilterType.SmallRectangular,

        // 设置颜色比较方法
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // 设置颜色量化方式
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // 将图片导出为PNG格式
    image.Save("ExportResult.png", new PngOptions());
}
```

### 也可以看看

* class [VectorImage](../../aspose.imaging/vectorimage)
* 命名空间 [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
