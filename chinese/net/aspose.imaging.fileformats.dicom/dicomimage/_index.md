---
title: "类 DicomImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Dicom.DicomImage 类。此类实现了医学数字成像与通信（DICOM）光栅图像格式的支持，并提供了一个用于精确且灵活地处理 DICOM 图像的综合解决方案。您可以无缝操作图像页，包括获取、添加或删除页面以及控制默认和活动页面。它具备处理 alpha 通道、嵌入 XMP 元数据、调整大小、旋转、裁剪、二值化、调节、应用滤镜以及转换为其他光栅格式的能力。此 API 使开发人员能够有效地处理 DICOM 图像，同时满足医学成像环境中多样化的应用需求。"
type: docs
weight: 2500
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/
---
## DicomImage class

此类实现了医学数字成像与通信 (DICOM) 栅格图像格式的支持，并提供了一个全面的解决方案，用于精确且灵活地处理 DICOM 图像。您可以无缝操作图像页，包括获取、添加或删除页面，以及控制默认页和活动页。它具备处理 alpha 通道、嵌入 XMP 元数据、调整大小、旋转、裁剪、二值化、调节、应用过滤器以及转换为其他栅格格式的能力。此 API 使开发者能够有效地处理 DICOM 图像，同时满足医学影像领域中多样化的应用需求。

```csharp
public sealed class DicomImage : RasterCachedMultipageImage, IMultipageImageExt
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DicomImage](dicomimage/#constructor_1)(Stream) | 通过在此构造函数中使用 stream 参数创建 DicomImage 类的新实例。非常适合希望从现有数据流中以简化方式初始化 `DicomImage` 对象的开发人员。 |
| [DicomImage](dicomimage/#constructor_2)(Stream, LoadOptions) | 通过在此构造函数中使用 stream 和 loadOptions 参数，顺利初始化 DicomImage 类的新实例。非常适合渴望在项目中快速且高效使用 `DicomImage` 对象的开发人员。 |
| [DicomImage](dicomimage/#constructor)(DicomOptions, int, int) | 使用此构造函数轻松初始化 DicomImage 类的新实例，利用 dicomOptions 参数。非常适合希望在项目中快速高效地使用 `DicomImage` 对象的开发者。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.dicom/dicomimage/activepage/) { get; set; } | 使用此直观属性管理图像的活动页。非常适合希望在多页图像中动态切换页面、确保高效导航和处理的开发者。 |
| [ActivePageIndex](../../aspose.imaging.fileformats.dicom/dicomimage/activepageindex/) { get; } | 使用此直观属性轻松获取活动页的索引。非常适合希望快速访问多页图像中当前页索引、确保高效导航和处理的开发者。 |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | 获取图像的每像素位数。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [DicomPages](../../aspose.imaging.fileformats.dicom/dicomimage/dicompages/) { get; } | 使用此直观属性访问图像的页面。非常适合希望与图像中的各个页面交互、确保无缝导航和操作的开发者。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.dicom/dicomimage/fileformat/) { get; } | 使用此直观属性轻松检索文件格式值。非常适合希望快速获取图像文件格式、并根据文件类型进行高效处理的开发者。 |
| [FileInfo](../../aspose.imaging.fileformats.dicom/dicomimage/fileinfo/) { get; } | 使用此直观属性轻松检索 DICOM 文件中的重要头信息。非常适合希望快速获取 DICOM 文件中封装的关键细节、确保高效数据提取和分析的开发者。 |
| override [HasAlpha](../../aspose.imaging.fileformats.dicom/dicomimage/hasalpha/) { get; } | 使用此直观属性轻松获取图像是否具有 alpha 通道。非常适合希望确定图像是否包含透明度信息、在图像处理任务中精确处理 alpha 通道数据的开发者。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | 获取指示图像是否具有透明颜色的值。 |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | 获取或设置帧的 XMP 数据。 |
| override [PageCount](../../aspose.imaging.fileformats.dicom/dicomimage/pagecount/) { get; } | 使用此直观属性检索图像的总页数。非常适合希望快速获取图像页数、确保高效导航和管理的开发者。 |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.dicom/dicomimage/pages/) { get; } | 使用此直观属性访问图像的页面。非常适合希望与图像中的各个页面交互、确保无缝导航和操作的开发者。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | 获取图像透明颜色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | 获取图像宽度。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage/#addpage)() | 使用此简便方法在图像的页面列表末尾追加新页面。非常适合希望动态扩展多页图像的开发者，确保图像内容的无缝集成和组织。 |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage/#addpage_1)(RasterImage) | 通过此直观方法添加新页面，扩展您的图像集合。非常适合希望动态向多页图像追加页面的开发者，确保图像内容的无缝扩展和组织。 |
| override [AdjustBrightness](../../aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness/)(int) | 通过调整 *brightness*（亮度）来增强图像亮度，这是一种参数化方法，允许开发者精细调节图像的光度。此用户友好功能使开发者能够无缝操作图像亮度，提供对视觉美感的灵活性和控制。 |
| override [AdjustContrast](../../aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/)(float) | 使用此用户友好方法增强 [`Image`](../../aspose.imaging/image/) 对比度，该方法调整明暗区域之间的差异。轻松提升视觉清晰度和细节，为开发者提供直观的图像对比度控制，以实现最佳渲染。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/#adjustgamma)(float) | 通过伽马校正提升图像质量并进行调整，这是一种用于细调视觉外观的强大技术。非常适合旨在优化图像呈现、调整色彩平衡并确保在不同设备和环境中实现一致渲染的开发者。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/#adjustgamma_1)(float, float, float) | 通过对图像的红、绿、蓝分量独立应用伽马校正，实现精确的颜色调整。此方法确保准确的色彩平衡和最佳的视觉输出，满足寻求对图像渲染和颜色精度进行细粒度控制的开发者需求。 |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | 计算提取数据与原始密码之间的相似度百分比。 |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | 自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.imaging.fileformats.dicom/dicomimage/binarizebradley/#binarizebradley_1)(double, int) | 使用 Bradley 自适应阈值算法进行图像二值化，利用积分图阈值提升性能。适用于希望根据局部亮度变化自动分割图像的开发者，确保在不同光照条件下实现准确的目标检测和提取。 |
| override [BinarizeFixed](../../aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/)(byte) | 使用此简便方法通过预定义阈值轻松将图像转换为二进制格式。适用于希望通过根据指定强度水平将图像分割为前景和背景来简化图像处理任务的开发者。 |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu/)() | 应用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳阈值。非常适合希望以最少人工干预将图像分割为前景和背景区域的开发者。 |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [CacheData](../../aspose.imaging.fileformats.dicom/dicomimage/cachedata/)() | 此方法高效缓存数据，优化性能并在需要时确保快速访问。适用于希望通过智能管理数据资源来提升应用程序速度和效率的开发者。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop/#crop)(Rectangle) | 使用此简易方法裁剪图像，去除不需要的区域并聚焦核心内容。适用于希望自定义图像视觉构图、确保有效传达预期信息的开发者。 |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop/#crop_1)(int, int, int, int) | 通过此多功能方法应用位移来调整图像的裁剪区域。非常适合需要对裁剪过程进行精确控制、在保留重要细节的同时去除不必要元素的开发者。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging.fileformats.dicom/dicomimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 使用此简便方法对当前图像应用抖动效果以进行增强。非常适合希望为图像添加纹理和深度、提升视觉质量和整体吸引力的开发者。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| override [Filter](../../aspose.imaging.fileformats.dicom/dicomimage/filter/)(Rectangle, FilterOptionsBase) | 轻松通过对指定矩形区域应用滤镜来增强图像的特定区域。此方法为开发者提供对图像操作的精确控制，轻松实现针对性调整，以达到期望的视觉效果。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | 获取资源图像最近修改的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。 |
| override [Grayscale](../../aspose.imaging.fileformats.dicom/dicomimage/grayscale/)() | 轻松将图像转换为灰度表示，简化视觉分析和处理任务。非常适合希望提升图像清晰度、降低复杂度并促进高效基于灰度的算法在各种应用中使用的开发者。 |
| [InsertPage](../../aspose.imaging.fileformats.dicom/dicomimage/insertpage/)(int) | 使用此直观方法在图像的页面列表中指定索引处插入新页面。非常适合希望对多页图像的页面排列进行精确控制，确保图像内容的无缝组织和自定义的开发者。 |
| override [IsDigitalSigned](../../aspose.imaging/rastercachedmultipageimage/isdigitalsigned/)(string, int) | 快速检查图像是否已数字签名，使用提供的密码和阈值。 |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels/)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels/)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels/)(Rectangle) | 加载 CMYK 格式的像素。 |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 按包部分加载 32 位 ARGB 像素。 |
| [LoadPartialArgb64Pixels](../../aspose.imaging/rasterimage/loadpartialargb64pixels/)(Rectangle, IPartialArgb64PixelLoader) | 按包部分加载 64 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 按包部分加载像素。 |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels/)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)() | 归一化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.imaging/rasterimage/rotate/) 方法。 |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle/)(bool, Color) | 归一化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate/) 方法。 |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedmultipageimage/normalizehistogram/)() | 归一化图像直方图——调整像素值以使用全部可用范围。 |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | 通过将此[`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) 值设为 `null` 来移除此图像实例的元数据。 |
| [RemovePage](../../aspose.imaging.fileformats.dicom/dicomimage/removepage/)(int) | 使用此便捷方法从页面列表中删除指定索引处的页面。非常适合希望对多页图像的管理进行精确控制，确保图像内容的无缝组织和自定义的开发者。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize/#resize_1)(int, int, ImageResizeSettings) | 使用此简单的调整大小方法调整图像尺寸。无论是需要缩小还是放大图像，此函数都能高效、准确地满足您的调整需求，使其成为寻求快速简便图像尺寸调整的开发者的理想选择。 |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize/#resize_2)(int, int, ResizeType) | 使用此直接的方法调整图像尺寸。非常适合希望动态调整图像大小，使其在应用程序的各种上下文和布局中无缝适配的开发者。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 使用此用户友好的方法在保持宽高比的同时调整图像高度。非常适合希望在动态调整图像大小时保持比例的开发者，确保在其应用中实现最佳显示和可用性。 |
| [ResizeProportional](../../aspose.imaging.fileformats.dicom/dicomimage/resizeproportional/)(int, int, ResizeType) | 使用此便捷方法在保持宽高比的情况下调整图像大小。适用于希望按比例调整图像尺寸的开发者，确保一致性并保留原始内容的比例。比例缩放将根据 *newWidth*/width 和 *newHeight*/height 的比率来调整每帧的大小。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 使用此便捷方法在保持宽高比的情况下调整图像宽度。适用于希望按比例缩放图像的开发者，确保在不同显示环境中获得一致且视觉上令人满意的效果。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.dicom/dicomimage/rotate/#rotate_1)(float, bool, Color) | 使用此便捷方法围绕中心旋转图像。适用于希望动态调整图像方向的开发者，确保在应用程序中实现最佳展示和对齐。 |
| override [RotateFlip](../../aspose.imaging.fileformats.dicom/dicomimage/rotateflip/)(RotateFlipType) | 使用此简洁方法轻松对活动帧进行旋转、翻转或同时执行两者操作。适用于需要在图像序列中动态调整特定帧方向的开发者，确保最佳展示和对齐。 |
| [Save](../../aspose.imaging/image/save/)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save/)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.imaging.fileformats.dicom/dicomimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 使用此便捷方法轻松将图像数据保存到指定流中的所需文件格式。无论是 JPEG、PNG 还是其他格式，此函数都能确保图像数据高效、准确地保存，非常适合希望简化文件保存流程的开发者。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveAll](../../aspose.imaging.fileformats.dicom/dicomimage/saveall/)(string, ImageOptionsBase) | 通过将对象的数据保存到指定的文件（索引器+文件名）位置，并使用指定的文件格式和选项来保留数据。适用于希望在多种格式中安全存储数据，同时保持对保存参数的灵活性和控制的开发者。 |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| override [SetResolution](../../aspose.imaging.fileformats.dicom/dicomimage/setresolution/)(double, double) | 使用此简洁方法精确调整此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的分辨率。适用于希望根据特定需求定制图像分辨率的开发者，确保最佳显示质量和文件大小管理。 |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | 将光栅图像转换为位图。此方法在 .Net7.0 及更高版本中不受支持。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

更改 DICOM 压缩中的颜色类型。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

在 DICOM 图像中使用 RLE 压缩。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

在 DICOM 图像中使用 JPEG 2000 压缩。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

在 DICOM 图像中使用 JPEG 压缩。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

此示例展示了如何从文件流加载 DICOM 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DICOM 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // 将每页保存为单独的 PNG 图像。                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // 根据页索引生成文件名。
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // DICOM 页面是栅格图像，因此所有对栅格图像允许的操作都适用于 DICOM 页面。
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

创建多页 Dicom 图像。

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // 使用矢量图形绘制内容
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // 保存绘制图像的像素。它们现在位于 Dicom 图像的第一页。
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // 在后面添加几页，使其更暗
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // 在主页面前添加几页，使其更亮
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // 将创建的多页图像保存到输出文件
    image.Save("MultiPage.dcm");
}
```

### 另请参见

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../aspose.imaging.fileformats.dicom/)
* assembly [Aspose.Imaging](../../)


