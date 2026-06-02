---
title: "类 WebPImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Webp.WebPImage 类。使用我们的 API 操作 WebP 栅格图像，利用其现代特性实现无损和有损压缩，确保在减小文件大小的同时获得最佳图像质量。无缝处理扩展文件格式、动画和 alpha 通道，同时轻松更新尺寸、等比例缩放、裁剪、旋转、应用滤镜、调整图像参数并转换为其他图像格式，以实现多功能的网页图像优化。"
type: docs
weight: 8260
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/
---
## WebPImage class

使用我们的 API 操作 WebP 栅格图像，利用其现代特性实现无损和有损压缩，确保在减小文件尺寸的同时获得最佳图像质量。无缝处理扩展文件格式、动画和 Alpha 通道，同时轻松更新尺寸、等比例缩放、裁剪、旋转、应用滤镜、调整图像参数，并转换为其他图像格式，以实现多功能的网页图像优化。

```csharp
public sealed class WebPImage : RasterCachedMultipageImage, IMultipageImageExt
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WebPImage](webpimage/#constructor)(RasterImage) | 实例化 `WebPImage` 类的新实例，使用提供的 rasterImage 对象进行初始化。此构造函数允许无缝将栅格图像转换为 WebP 格式，便于在您的应用程序中高效处理和操作图像数据。 |
| [WebPImage](webpimage/#constructor_4)(Stream) | 实例化 `WebPImage` 类的新实例，使用提供的流源进行初始化。利用此构造函数可直接从流中无缝创建 WebP 图像对象，便于在您的应用程序中高效处理和操作 WebP 图像数据。 |
| [WebPImage](webpimage/#constructor_6)(string) | 实例化 `WebPImage` 类的全新实例，使用提供的文件源进行初始化。利用此构造函数可直接从文件中无缝创建 WebP 图像对象，简化在您的应用程序中加载和操作 WebP 图像数据的过程。 |
| [WebPImage](webpimage/#constructor_1)(RasterImage, LoadOptions) | 使用 rasterImage 对象和指定的加载选项创建 `WebPImage` 类的新实例，以实现对图像数据的灵活处理。利用此构造函数可无缝地从栅格图像初始化 WebP 图像对象，并根据您的应用程序需求自定义加载参数。 |
| [WebPImage](webpimage/#constructor_5)(Stream, LoadOptions) | 从流创建 `WebPImage` 类的新实例，结合指定的加载选项和内存管理设置。此构造函数在从流加载 WebP 图像时提供灵活性，同时高效管理内存资源，确保在您的应用程序中实现最佳性能和资源利用率。 |
| [WebPImage](webpimage/#constructor_7)(string, LoadOptions) | 使用文件和指定的加载选项创建 `WebPImage` 类的新实例，以便灵活处理 WebP 图像数据。利用此构造函数可无缝地从文件初始化 WebP 图像对象，并根据您的应用程序需求自定义加载参数。 |
| [WebPImage](webpimage/#constructor_2)(int, int, WebPOptions) | 实例化 `WebPImage` 类的新实例，使用指定宽度和高度的空白图像。此构造函数允许创建空白的 WebP 图像，为后续的图像操作和内容生成提供基础。 |
| [WebPImage](webpimage/#constructor_3)(int, int, WebPOptions, LoadOptions) | 使用空白图像和指定的加载选项创建 `WebPImage` 类的新实例。此构造函数允许使用可自定义的加载参数初始化 WebP 图像，为您的应用程序提供图像创建和操作的灵活性。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | 获取图像的每像素位数。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.webp/webpimage/fileformat/) { get; } | 访问与图像关联的文件格式值，提供图像存储格式的信息。利用此属性可确定图像的文件格式，便于在您的应用程序中进行兼容性检查和特定格式的处理。 |
| override [HasAlpha](../../aspose.imaging.fileformats.webp/webpimage/hasalpha/) { get; } | 检索图像是否包含 alpha 通道，以指示是否存在透明度信息。利用此属性确定图像是否包含透明度，从而在应用程序中适当处理和处理与 alpha 相关的操作。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | 获取指示图像是否具有透明颜色的值。 |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | 获取或设置帧的 XMP 数据。 |
| [Options](../../aspose.imaging.fileformats.webp/webpimage/options/) { get; } | 检索或修改指定属性关联的选项，以实现行为和设置的精细定制。利用此属性无缝访问和操控可配置参数，促进在应用程序功能中的多样化控制和优化。 |
| override [PageCount](../../aspose.imaging.fileformats.webp/webpimage/pagecount/) { get; } | 检索指定文档的总页数，以便高效导航和管理多页内容。将此功能整合到用户体验中，实现对完整文档结构的无缝访问。 |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.webp/webpimage/pages/) { get; } | 访问图像中的 WebP 块，允许对底层块结构进行详细检查或操作。利用此属性分析或修改 WebP 图像数据中的各个块，促进在应用程序中进行高级图像处理技术。 |
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
| [AddBlock](../../aspose.imaging.fileformats.webp/webpimage/addblock/)(IFrame) | 在图像中加入新的 WebP 块，丰富其内容并促进高级图像操作。将此方法集成到应用程序中，以动态增强 WebP 图像数据的结构和复杂度，实现对图像渲染的精确控制和优化。 |
| [AddPage](../../aspose.imaging.fileformats.webp/webpimage/addpage/)(RasterImage) | 向图像追加新页面，扩展其内容并容纳额外的视觉元素。将此方法集成到应用程序中，以促进动态页面管理，实现多页文档或图像的无缝创建和增补。 |
| override [AdjustBrightness](../../aspose.imaging.fileformats.webp/webpimage/adjustbrightness/)(int) | 实现对图像的 *brightness* 调整，允许修改整体亮度水平。将此方法纳入图像处理工作流，以提升可见性并改善应用程序中图像的视觉质量。 |
| override [AdjustContrast](../../aspose.imaging.fileformats.webp/webpimage/adjustcontrast/)(float) | 增强 [`Image`](../../aspose.imaging/image/) 的对比度，放大明暗区域之间的差异。将此方法集成到图像处理工作流，以提升视觉清晰度和整体图像质量。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma/#adjustgamma)(float) | 对图像应用伽马校正，调整像素强度以实现所需的亮度和色彩平衡。将此方法纳入图像处理工作流，以提升视觉质量并改进后续分析或显示任务的准确性。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma/#adjustgamma_1)(float, float, float) | 使用红、绿、蓝通道的单独系数对图像执行伽马校正，允许对色彩平衡和对比度进行精细调节。将此方法集成到图像处理管道，以实现对色彩渲染的精确控制并提升视觉保真度。 |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | 计算提取数据与原始密码之间的相似度百分比。 |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | 自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.imaging.fileformats.webp/webpimage/binarizebradley/#binarizebradley_1)(double, int) | 使用 Bradley 的自适应阈值算法结合积分图阈值，对图像进行二值化。此方法根据图像邻域动态计算局部阈值，增强对不同光照条件的适应性，并确保后续处理任务的稳健分割。 |
| override [BinarizeFixed](../../aspose.imaging.fileformats.webp/webpimage/binarizefixed/)(byte) | 使用预定义阈值对图像进行二值化，将其转换为二进制图像，像素根据相对于阈值的强度被分类为前景或背景。将此方法纳入图像处理工作流，以促进分割和特征提取任务，提升后续分析的准确性和效率。 |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.webp/webpimage/binarizeotsu/)() | 使用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳阈值。将此方法集成到图像处理工作流，以实现有效的分割和特征提取，提升图像分析任务的准确性和可靠性。 |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | 缓存数据为私有。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| [ClearBlocks](../../aspose.imaging.fileformats.webp/webpimage/clearblocks/)() | 清除图像中所有现有的 WebP 块，为后续修改或添加提供干净的起点。利用此方法有效重置 WebP 图像数据中的块结构，确保在应用程序中对图像内容进行最佳管理和组织。 |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop/#crop)(Rectangle) | 使用指定的矩形区域裁剪图像，去除不需要的部分同时保留所需内容。将此方法集成到图像处理工作流，以精确提取并聚焦图像中的特定感兴趣区域，提升各种应用的清晰度和构图。 |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop/#crop_1)(int, int, int, int) | 通过左右上下偏移裁剪图像，有效选择图像中的感兴趣区域。利用此方法动态提取所需的图像部分，并根据应用需求调整其构图和焦点。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging.fileformats.webp/webpimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动处理，以降低颜色带状效应并提升视觉质量。将此方法纳入图像处理工作流，以实现颜色之间更平滑的过渡，改善图像的整体外观。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| override [Filter](../../aspose.imaging.fileformats.webp/webpimage/filter/)(Rectangle, FilterOptionsBase) | 在指定的矩形内过滤内容，应用指定的图像处理滤镜以增强或修改所选区域。将此方法集成到图像操作工作流，以在应用程序中实现针对性的增强或转换。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | 获取资源图像最近修改的日期和时间。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.webp/webpimage/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。 |
| override [Grayscale](../../aspose.imaging.fileformats.webp/webpimage/grayscale/)() | 将图像转换为灰度表示，转化为单通道图像，每个像素表示强度或亮度。将此方法集成到图像处理管道，以简化分析并提升与基于灰度算法的兼容性，促进各种计算机视觉和图像分析任务。 |
| [InsertBlock](../../aspose.imaging.fileformats.webp/webpimage/insertblock/)(int, IFrame) | 在图像的指定索引处插入新的 WebP 块，实现对块顺序的精确控制。将此方法无缝整合到图像数据结构中，以便在应用程序中加入额外的 WebP 块，促进高级图像处理和优化。 |
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
| [RemoveBlock](../../aspose.imaging.fileformats.webp/webpimage/removeblock/)(IFrame) | 从图像中移除指定的 WebP 块，以实现对图像数据结构的高效管理。利用此方法通过消除不必要的块或组件来简化图像处理工作流。 |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | 通过将此[`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) 值设为 `null` 来移除此图像实例的元数据。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize/#resize_1)(int, int, ImageResizeSettings) | 根据指定设置调整图像大小，实现对尺寸、宽高比和缩放行为的精确控制。将此方法集成到图像处理工作流，以实现针对应用程序特定需求的自定义缩放操作。 |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize/#resize_2)(int, int, ResizeType) | 调整图像大小，同时保持宽高比。将此方法集成到图像处理工作流，以动态缩放图像以适应各种显示或存储需求。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 按比例调整图像高度，同时保持宽高比以实现一致的缩放。将此方法集成到图像处理工作流，以统一比例动态调整图像大小，确保在应用程序中的最佳显示或存储。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 按比例调整图像宽度，同时保持宽高比。将此方法集成到图像处理工作流，以统一比例动态调整图像大小，确保在应用程序中的最佳显示或存储。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.webp/webpimage/rotate/#rotate_1)(float, bool, Color) | 按指定角度围绕图像中心旋转图像，同时按比例调整大小并应用指定的背景颜色参数。将此方法整合到您的图像处理工作流中，以实现可定制背景颜色的精确转换，确保在应用程序中获得最佳视觉呈现。 |
| override [RotateFlip](../../aspose.imaging.fileformats.webp/webpimage/rotateflip/)(RotateFlipType) | 仅对图像中的活动帧应用旋转、翻转或两者的操作。将此方法整合到您的图像处理工作流中，以实现对单个帧的精确操作，提升在应用程序中对帧转换的灵活性和控制力。 |
| [Save](../../aspose.imaging/image/save/)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save/)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.imaging/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | 设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的分辨率。 |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | 将光栅图像转换为位图。此方法在 .Net7.0 及更高版本中不受支持。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

此示例展示了如何从文件加载 WebP 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // 保存为 PNG
    // 请注意，由于 PNG 不是多页格式，仅会将活动帧存储为 PNG。
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Webp](../../aspose.imaging.fileformats.webp/)
* assembly [Aspose.Imaging](../../)


