---
title: "类 EpsImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Eps.EpsImage 类。该 API 用于封装的 PostScript (EPS) 图像文件格式的支持，提供了强大的功能来操作包含文本、图形和图像的组合。具备位图预览图像处理、方向翻转、获取插图边界的边界框、调整大小、旋转图像以及添加预览图像等特性，此 API 确保在各种应用中精确且多功能地无缝处理和集成 EPS 文件。"
type: docs
weight: 6670
url: /zh/net/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

用于 Encapsulated PostScript (EPS) 图像文件格式支持的 API 提供了强大的功能，可对包含文本、图形和图像的组合进行操作。具备位图预览图像处理、方向翻转、获取插图边界的边界框、调整大小、旋转图像以及添加预览图像等特性，此 API 确保在各种应用中以精确且多功能的方式无缝处理和集成 EPS 文件。

```csharp
public sealed class EpsImage : VectorImage
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel/) { get; } | 使用此属性可轻松获取图像的精确位深。检索每像素位数，提供有关图像颜色深度的关键洞察，并有助于优化处理任务。非常适合需要对图像操作和分析进行细粒度控制的应用程序。 |
| [BoundingBox](../../aspose.imaging.fileformats.eps/epsimage/boundingbox/) { get; } | 通过以设备无关点访问原始边界框，此属性提供关于 `EpsImage` 尺寸的关键几何信息。检索这些数据后，用户可以准确评估图像的大小和宽高比，从而在各种应用中实现精确的布局和定位。 |
| [BoundingBoxPx](../../aspose.imaging.fileformats.eps/epsimage/boundingboxpx/) { get; } | 此属性以像素返回 `EpsImage` 实例的原始边界框，提供用于精确渲染和操作的关键几何数据。有了这些信息，用户可以确保在项目中对 EPS 图像进行精确的放置和尺寸 /// 调整，提升整体视觉呈现和质量。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate/) { get; } | 从 EPS 文档结构约定 (DSC) 注释中检索创建日期，此属性提供指示 EPS 文件生成时间的关键元数据。通过访问这些信息，用户可了解文件的来源和时间顺序，提升文件管理和组织效率。 |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator/) { get; } | 此属性可访问来自 EPS 文件中 EPS 文档结构约定 (DSC) 注释的创建者信息。了解创建者细节可洞悉生成 EPS 文件所使用的软件或工具，便于在各种平台和应用之间进行兼容性评估。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype/) { get; } | 访问并解释 EPS 图像的子类型值，简化工作流并提升跨平台兼容性。非常适合在项目中以精确高效的方式优化 EPS 子类型的检索。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat/) { get; } | 使用此属性访问图像的文件格式。检索有关图像文件格式的关键信息，促进兼容性和高效处理。非常适合识别图像文件的格式，以便在项目中实现无缝集成。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview/) { get; } | 轻松发现栅格预览的存在。访问布尔值以指示 `EpsImage` 实例是否包含栅格预览，为您的图像处理任务提供清晰高效的支持。非常适合根据 EPS 图像中栅格预览的有无来简化工作流决策。 |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | 获取图像高度。 |
| override [HeightF](../../aspose.imaging.fileformats.eps/epsimage/heightf/) { get; } | 使用此属性访问图像的高度。轻松获取图像高度，以实现无缝的布局调整、宽高比计算以及在不同屏幕分辨率和显示环境下的精确渲染。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached/) { get; } | 此属性提供了一种便捷方式来检查对象的数据是否已缓存，消除额外读取数据的需求。它提供快速高效的方法来确定所需信息是否已就绪，从而优化性能并降低数据密集型操作的资源开销。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion/) { get; } | 此属性检索与 `EpsImage` 实例关联的 PostScript 版本。它提供对 EPS 文件中使用的特定 PostScript 语言版本的洞察，有助于兼容性评估并促进与支持 PostScript 的环境的无缝集成。 |
| [PreviewImageCount](../../aspose.imaging.fileformats.eps/epsimage/previewimagecount/) { get; } | 轻松访问可用预览图像的数量。此属性让您轻松检索与文件关联的预览图像计数，便于高效管理和导航图像预览。非常适合优化工作流并有效组织图像资产。 |
| [PreviewImages](../../aspose.imaging.fileformats.eps/epsimage/previewimages/) { get; } | 检索与文件关联的预览图像。此属性提供对预览图像集合的无缝访问，使您能够高效浏览和管理所需的图像。非常适合快速预览并为项目选择合适的图像。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title/) { get; } | 此属性检索从 EPS 文档结构约定（DSC）注释中提取的标题，这些注释嵌入在 EPS 文件中。它提供有关 EPS 文件内容的有价值元数据，有助于在兼容软件应用中进行文档组织和识别。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | 获取图像宽度。 |
| override [WidthF](../../aspose.imaging.fileformats.eps/epsimage/widthf/) { get; } | 使用此便捷属性检索图像的宽度。轻松获取图像宽度，便于精确的布局计算、缩放操作以及在应用程序中的尺寸相关任务。非常适合确保在各种平台和设备上准确渲染和显示图像。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata/)() | 此方法不执行任何操作，因为当前 `EpsImage` 类的实现不涉及缓存数据。虽然它可能不执行任何动作，但了解此行为对使用 EPS 图像的开发者至关重要，以确保在应用程序中实现高效的资源管理和最佳性能。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | 裁剪指定的矩形。 |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | 获取默认的图像选项。 |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | 获取嵌入的图像。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
| [GetPreviewImage](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimage/)(EpsPreviewFormat) | 检索指定 *format* 的现有预览图像，如果未找到则返回 `null`。此方法在访问针对特定格式定制的预览图像时提供灵活性，优化应用程序中的兼容性和资源管理。 |
| [GetPreviewImages](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimages/)() | 访问链接到 `EpsImage` 实例的预览图像，允许在应用程序中无缝检索以进行检查或使用。此方法提供便捷的预览图像访问，增强用户对图像数据的交互体验。 |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | 移除背景。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | 移除背景。 |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | 移除元数据。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | 使用扩展选项调整图像大小。 |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | 调整指定的新宽度。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.imaging/vectorimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | 旋转、翻转或同时旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save/)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save/)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette/)(IColorPalette, bool) | 自定义图像调色板以实现独特的配色方案并提升视觉吸引力。轻松为特定效果调整颜色，并在不同平台和设备上优化图像质量。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |

## 示例

调整 EPS 图像大小并导出为 PNG 格式。

```csharp
[C#]

// 加载 EPS 图像
using (var image = Image.Load("AstrixObelix.eps"))
{
    // 使用 Mitchell 三次插值方法调整图像大小
    image.Resize(400, 400, ResizeType.Mitchell);

    // 将图像导出为 PNG 格式
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
            PdfCompliance = PdfComplianceVersion.PdfA1b // Set required PDF compliance
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
            PageWidth = 500, // Image width
            PageHeight = 500 // Image height
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // Render raster image using the PostScript
        }
    };

    image.Save("Sample.png", options);
}
```

使用高级设置调整 EPS 图像大小。

```csharp
[C#]

// 加载 EPS 图像
using (var image = Image.Load("AstrixObelix.eps"))
{
    // 使用高级缩放设置调整图像大小
    image.Resize(400, 400, new ImageResizeSettings
    {
        // 设置插值模式
        Mode = ResizeType.LanczosResample,

        // 设置过滤器类型
        FilterType = ImageFilterType.SmallRectangular,

        // 设置颜色比较方法
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // 设置颜色量化方法
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // 将图像导出为 PNG 格式
    image.Save("ExportResult.png", new PngOptions());
}
```

### 另请参见

* class [VectorImage](../../aspose.imaging/vectorimage/)
* namespace [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps/)
* assembly [Aspose.Imaging](../../)


