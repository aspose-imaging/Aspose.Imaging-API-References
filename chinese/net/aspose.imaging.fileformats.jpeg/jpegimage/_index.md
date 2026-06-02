---
title: "类 JpegImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Jpeg.JpegImage 类。使用我们的 API 高效操作 JPEG 栅格图像，支持多种颜色配置文件，如 RGB 和 CMYK，可自定义每像素位深分辨率，并处理 EXIF、JFIF 和 XMP 元数据容器。享受基于方向数据的自动旋转，并可从包括无损 JPEG 在内的不同压缩级别中选择，以实现项目中图像质量与文件大小的最佳平衡。"
type: docs
weight: 6880
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/
---
## JpegImage class

使用我们的 API 高效地操作 JPEG 栅格图像，提供对 RGB、CMYK 等多种颜色配置文件的支持，可自定义每像素位数分辨率，并处理 EXIF、JFIF 和 XMP 元数据容器。享受基于方向数据的自动旋转，并可从包括无损 JPEG 在内的不同压缩级别中进行选择，以实现项目中图像质量与文件大小的最佳平衡。

```csharp
public sealed class JpegImage : RasterCachedImage, IHasJpegExifData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [JpegImage](jpegimage/#constructor_1)(RasterImage) | 使用栅格图像参数初始化 `JpegImage` 类的新实例。此构造函数提供了一种便捷方式，可直接从栅格图像创建 JPEG 图像，简化在应用程序中处理 JPEG 图像的工作流。 |
| [JpegImage](jpegimage/#constructor_3)(Stream) | 使用流参数通过 `JpegImage` 类初始化 JPEG 图像对象。此构造函数简化了处理 JPEG 图像的过程，提供了一种直接的方法，可轻松将其集成到您的项目中。 |
| [JpegImage](jpegimage/#constructor_4)(string) | `JpegImage` 类通过使用指定的路径参数调用其构造函数即可轻松初始化。此构造函数实现了 JPEG 图像的无缝创建，确保轻松快速地将其集成到您的项目中。 |
| [JpegImage](jpegimage/#constructor_2)(int, int) | 使用指定的宽度和高度参数创建 `JpegImage` 类的新实例。此构造函数允许您创建具有自定义尺寸的 JPEG 图像，为在应用程序中管理图像大小提供了灵活性。 |
| [JpegImage](jpegimage/#constructor)(JpegOptions, int, int) | 使用提供的 JPEG 选项初始化新的 `JpegImage` 对象。此构造函数使您能够定制 JPEG 图像的各种设置，如压缩级别、质量和其他参数，从而对生成的图像格式进行精确控制。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg/jpegimage/bitsperpixel/) { get; } | 使用此属性轻松获取图像的像素深度，提供对颜色或灰度表现丰富度的洞察。无论是鲜艳的照片还是单色插图，此属性都提供了关于图像视觉复杂性的关键信息。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [CmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/cmykcolorprofile/) { get; set; } | 与 CMYK 和 YCCK JPEG 图像关联的 CMYK 颜色配置文件确保精确的颜色转换和保真度。它与 RGBColorProfile 协同工作，以保证在各种设备和应用程序中的准确颜色呈现。此组合对于保持颜色渲染的一致性并实现最佳图像质量至关重要。 |
| [Comment](../../aspose.imaging.fileformats.jpeg/jpegimage/comment/) { get; set; } | 使用此属性管理 JPEG 文件注释，允许您添加或检索与图像关联的描述性标注。无论是使用元数据标记图像还是添加额外的上下文，此属性都提供了组织和分类 JPEG 文件的灵活性。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [DestinationCmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationcmykcolorprofile/) { get; set; } | 在保存过程中，CMYK 颜色配置文件对于 CMYK 和 YCCK JPEG 图像的准确颜色转换至关重要。它与 RGBColorProfile 协同工作，以确保正确的颜色呈现，保持不同设备和软件之间的一致性和质量。此同步对于在最终保存的图像中实现准确可靠的颜色渲染至关重要。 |
| [DestinationRgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationrgbcolorprofile/) { get; set; } | 在保存过程中，RGBColorProfile 对于 CMYK 和 YCCK JPEG 图像的准确颜色转换至关重要。与 CMYKColorProfile 配合使用时，它确保颜色正确渲染，并在不同设备和应用程序之间保持一致性。此组合对于保留预期的颜色呈现并实现高质量图像输出至关重要。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging.fileformats.jpeg/jpegimage/exifdata/) { get; set; } | 使用此属性管理 EXIF 数据，允许您添加或检索与图像关联的元数据。无论是提取相机设置信息还是修改现有元数据，此属性都提供了管理 EXIF 数据容器的灵活性。（2 个属性） |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/fileformat/) { get; } | 使用此属性轻松检索图像的格式。它提供了对文件格式的有价值洞察，有助于在各种平台和应用程序之间实现无缝集成和兼容性检查。 |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | 获取或设置一个值，指示此 [`RasterImage`](../../aspose.imaging/rasterimage/) 实例是否具有透明颜色。 |
| override [Height](../../aspose.imaging.fileformats.jpeg/jpegimage/height/) { get; } | 使用此属性轻松获取图像的高度。它快速访问图像的垂直尺寸，使您能够高效确定其大小和宽高比，无需复杂计算或额外方法。 |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution/) { get; set; } | 此属性允许您访问 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率，单位为每英寸像素。通过设置或获取此值，您可以精确控制图像的分辨率，确保满足对质量和清晰度的特定要求。 |
| [IgnoreEmbeddedColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/ignoreembeddedcolorprofile/) { get; set; } | 检索或修改标记是否忽略嵌入颜色配置文件的标志。通过设置此标志，用户可以指定是使用默认颜色配置文件还是嵌入的配置文件。此选项确保对颜色管理有更大的控制，便于在各种平台和应用程序之间进行一致性和兼容性的调整。 |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| [Jfif](../../aspose.imaging.fileformats.jpeg/jpegimage/jfif/) { get; set; } | 此属性允许您访问或修改与 JPEG 图像关联的 JFIF（JPEG 文件交换格式）数据。JFIF 是在计算机和其他设备之间交换 JPEG 压缩图像的标准格式。通过获取或设置此属性，您可以与 JFIF 数据交互，其中可能包括图像的分辨率、宽高比和缩略图等信息。 |
| [JpegOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/) { get; } | 轻松获取在创建或加载此 `JpegImage` 实例时使用的 JPEG 选项。此属性提供有关所使用的特定设置的有价值细节，使用户能够有效地理解和复制图像处理工作流。无论是压缩级别、质量设置还是其他参数，此属性都提供了实现无缝图像操作的关键洞察。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/rawdataformat/) { get; } | 此属性检索图像的原始数据格式，指示图像数据的结构和编码方式。了解原始数据格式对于有效处理或操作图像数据至关重要。它提供了对图像底层表示的洞察，例如是否已压缩、是否在特定色彩空间中编码，或是否存储在特定文件格式中。访问此属性可让您获取有关图像数据结构的有价值信息，从而能够执行针对其特定格式的各种操作或优化。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [RgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile/) { get; set; } | CMYK 和 YCCK JPEG 图像的 RGB 颜色配置文件可确保准确的颜色转换和呈现。它必须与 CMYKColorProfile 配对，以保持颜色渲染的一致性和保真度。此配对对于需要精确颜色管理和图像再现的应用程序至关重要，确保 RGB 数据得到正确解释和显示。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | 获取图像透明颜色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution/) { get; set; } | 此属性管理关联的 [`RasterImage`](../../aspose.imaging/rasterimage/) 的垂直分辨率，单位为每英寸像素数。调整此分辨率会影响图像在打印或以固定物理尺寸显示时的大小和质量。通过设置此属性，您可以控制图像像素在垂直方向上的密集程度，从而影响整体的清晰度和锐度。 |
| override [Width](../../aspose.imaging.fileformats.jpeg/jpegimage/width/) { get; } | 此属性检索图像的宽度，单位为像素。它提供有关图像尺寸的关键信息，使得图像数据的准确渲染、操作或显示成为可能。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness/)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast/)(float) | 图像对比度。 |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float) | 图像的伽马校正。 |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float, float, float) | 图像的伽马校正。 |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedimage/analyzepercentagedigitalsignature/)(string) | 计算提取数据与原始密码之间的相似度百分比。 |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | 自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double, int) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed/)(byte) | 使用预定义阈值对图像进行二值化 |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu/)() | 使用 Otsu 阈值法对图像进行二值化 |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [Blend](../../aspose.imaging/rastercachedimage/blend/)(Point, RasterImage, Rectangle, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) 加载额外数据。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging/rastercachedimage/crop/)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动处理。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedimage/embeddigitalsignature/)(string) | 使用隐写技术将基于提供的密码的数字签名嵌入图像中。 |
| virtual [Filter](../../aspose.imaging/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 过滤指定的矩形。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| override [GetModifyDate](../../aspose.imaging.fileformats.jpeg/jpegimage/getmodifydate/)(bool) | 检索资源图像最近一次修改的日期和时间。此方法提供有价值的元数据，使用户能够有效跟踪和管理图像文件的更新。通过访问此信息，用户可以确保其图像资产的完整性和时效性，从而在图像使用和维护方面做出明智的决策。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/getoriginaloptions/)() | 获取此 [`Image`](../../aspose.imaging/image/) 实例的原始图像选项。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。 |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale/)() | 将图像转换为灰度表示 |
| override [IsDigitalSigned](../../aspose.imaging/rastercachedimage/isdigitalsigned/)(string, int) | 快速检查图像是否已数字签名，使用提供的密码和阈值。 |
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
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)(bool, Color) | 归一化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.imaging/rasterimage/rotate/) 方法。 |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedimage/normalizehistogram/)() | 归一化图像直方图——调整像素值以使用全部可用范围。 |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| override [RemoveMetadata](../../aspose.imaging.fileformats.jpeg/jpegimage/removemetadata/)() | 通过将此 [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) 和 [`ExifData`](../../aspose.imaging.exif/ihasexifdata/exifdata/) 的值设为 `null` 来移除该图像实例的元数据。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(int, byte, int) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging/rastercachedimage/resize/)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate/)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip/)(RotateFlipType) | 旋转、翻转或同时旋转和翻转图像。 |
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
| override [SetResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/setresolution/)(double, double) | 为指定的 [`RasterImage`](../../aspose.imaging/rasterimage/) 设置分辨率，确保精确的缩放和打印能力。此方法使用户能够根据其特定需求（无论是数字显示还是实体复制）定制图像分辨率。通过设置分辨率，用户可以优化图像质量并确保与各种输出设备和介质的兼容性，提升整体视觉体验和图像的可用性。 |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | 将光栅图像转换为位图。此方法在 .Net7.0 及更高版本中不受支持。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

在 JPEG 图像中访问相机制造商的 Maker Note。

```csharp
[C#]

using (var image = (JpegImage)Image.Load("Sample.jpg"))
{
    foreach (var makerNote in image.ExifData.MakerNotes)
    {
        Console.WriteLine("Name = {0}, Value = {1}", makerNote.Name, makerNote.Value);
    }
}
```

示例展示了如何从文件加载 JpegImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 JPEG 图像。
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // 进行一些图像处理。
    // 保存为另一个 JPEG 文件。
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### 另请参见

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* interface [IHasJpegExifData](../../aspose.imaging.exif/ihasjpegexifdata/)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg/)
* assembly [Aspose.Imaging](../../)


