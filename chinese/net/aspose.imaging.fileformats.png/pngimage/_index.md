---
title: "类 PngImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Png.PngImage 类。使用我们功能强大的 API 操作便携式网络图形 PNG 栅格图像，支持压缩级别和多种颜色深度，包括灰度、索引颜色、真彩色和 alpha 通道。无缝处理 XMP 元数据，实现全面的图像元数据管理，同时轻松加载 PNG 图像，执行多样化的操作、应用滤镜并将图像转换为其他文件格式，以实现最佳的灵活性和自定义。"
type: docs
weight: 7560
url: /zh/net/aspose.imaging.fileformats.png/pngimage/
---
## PngImage class

使用我们多功能的 API 操作便携式网络图形（PNG）光栅图像，支持压缩级别和多种颜色深度，包括灰度、索引颜色、真彩色和 Alpha 通道。可无缝处理 XMP 元数据，实现全面的图像元数据管理，同时轻松加载 PNG 图像，执行多样化的操作，应用滤镜，并将图像转换为其他文件格式，以获得最佳的灵活性和定制化。

```csharp
public class PngImage : RasterCachedImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PngImage](pngimage/#constructor_1)(RasterImage) | 通过提供栅格图像作为参数来创建 `PngImage` 类的新实例。此构造函数允许开发者直接使用现有栅格图像初始化 PNG 图像对象，简化在应用程序中处理 PNG 图像的流程。 |
| [PngImage](pngimage/#constructor_5)(Stream) | 通过使用流进行初始化来创建 `PngImage` 类的新实例。此构造函数允许开发者直接从流加载 PNG 图像，为从不同来源获取图像提供灵活性。 |
| [PngImage](pngimage/#constructor_6)(string) | 使用路径参数指定要加载的图像文件位置，构造 `PngImage` 类的新实例。此构造函数使开发者能够方便地通过从文件加载来创建 PNG 图像，简化在应用程序中处理 PNG 图像的过程。 |
| [PngImage](pngimage/#constructor_3)(int, int) | 通过提供宽度和高度参数来初始化 `PngImage` 类的新对象。此构造函数通过允许开发者直接指定尺寸，简化 PNG 图像的创建，便于在应用程序中高效管理 PNG 图像数据。 |
| [PngImage](pngimage/#constructor_2)(RasterImage, PngColorType) | 通过指定栅格图像和颜色类型来创建 `PngImage` 类的新实例。此构造函数使开发者能够在指定所需颜色类型的同时直接将栅格图像转换为 PNG 格式，提供颜色表示的灵活性。 |
| [PngImage](pngimage/#constructor_7)(string, PngColorType) | 通过指定图像文件路径和颜色类型来初始化 `PngImage` 类的新实例。此构造函数方便地从具有不同颜色类型的文件创建 PNG 图像，提供处理各种图像格式的灵活性。 |
| [PngImage](pngimage/#constructor_4)(int, int, PngColorType) | 实例化 `PngImage` 类的全新实例，指定所需的宽度、高度和颜色类型参数。此构造函数实现快速创建具有定制尺寸和颜色配置的 PNG 图像，促进各种应用和工作流的高效图像生成。 |
| [PngImage](pngimage/#constructor)(PngOptions, int, int) | 初始化 `PngImage` 类的新实例，结合 PNG 选项以及宽度和高度参数。此构造函数使开发者能够创建具有可自定义设置和尺寸的 PNG 图像，为多种使用场景的图像生成提供灵活性。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging.fileformats.png/pngimage/backgroundcolor/) { get; set; } | 检索图像的背景颜色（如果已指定）。此属性对需要识别并可能操作图像背景颜色的应用程序很有帮助。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.png/pngimage/bitsperpixel/) { get; } | 获取图像的每像素位数值。此属性提供有关图像颜色深度的关键信息，使开发者能够了解图像数据中细节和颜色精度的水平。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.png/pngimage/fileformat/) { get; } | 检索与图像实例关联的文件格式。此属性提供有关文件类型的基本信息，便于根据特定格式要求进行高效处理。 |
| override [HasAlpha](../../aspose.imaging.fileformats.png/pngimage/hasalpha/) { get; } | 返回一个布尔值，指示图像是否具有 alpha 通道，从而决定其透明度。此属性对需要处理透明度的应用程序有用，帮助开发者判断是否需要额外处理图像中的透明区域。 |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/) { get; set; } | 检索一个布尔值，指示图像是否具有背景颜色。此属性对需要判断图像是否包含背景颜色的应用程序有用，这在合成、渲染或导出等各种处理任务中可能很重要。 |
| override [HasTransparentColor](../../aspose.imaging.fileformats.png/pngimage/hastransparentcolor/) { get; set; } | 提供一个布尔值，指示图像是否包含透明颜色。此属性对需要处理透明度的应用程序至关重要，帮助开发者判断是否需要额外处理图像中的透明区域。 |
| override [Height](../../aspose.imaging.fileformats.png/pngimage/height/) { get; } | 获取图像的高度。此属性返回图像的垂直尺寸，帮助开发者确定其在垂直轴上的像素大小。 |
| override [HorizontalResolution](../../aspose.imaging.fileformats.png/pngimage/horizontalresolution/) { get; set; } | 检索或修改图像的水平分辨率。此属性表示图像水平轴上每英寸的像素数。调整该分辨率会影响图像在打印或显示时的实际尺寸。 |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [Interlaced](../../aspose.imaging.fileformats.png/pngimage/interlaced/) { get; } | 检索一个布尔值，指示 `PngImage` 是否为隔行扫描，这决定图像数据是否以渐进方式存储以实现更快的加载或传输。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsInterlaced](../../aspose.imaging.fileformats.png/pngimage/isinterlaced/) { get; } | 返回一个布尔值，指示图像实例是否为隔行扫描。此属性对优化加载策略并确保图像处理或显示任务期间的高效性能至关重要。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| override [RawDataFormat](../../aspose.imaging.fileformats.png/pngimage/rawdataformat/) { get; } | 访问图像的原始数据格式。此属性提供对图像数据内部结构的洞察，可用于高级图像处理任务或格式转换。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| override [TransparentColor](../../aspose.imaging.fileformats.png/pngimage/transparentcolor/) { get; set; } | 检索图像的透明颜色（如果存在）。此属性对需要精确处理图像内部透明区域的应用程序非常有价值，允许开发者访问并操作所使用的特定透明颜色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| override [VerticalResolution](../../aspose.imaging.fileformats.png/pngimage/verticalresolution/) { get; set; } | 提供对图像垂直分辨率的访问。开发人员可以使用此属性检索或修改分辨率设置，该设置指示图像垂直轴上每英寸的像素数（PPI）。 |
| override [Width](../../aspose.imaging.fileformats.png/pngimage/width/) { get; } | 允许检索图像的宽度，提供有关其尺寸的基本信息。开发人员经常使用此属性来确定图像的宽度，从而能够基于其大小执行各种操作。 |
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
| override [GetDefaultOptions](../../aspose.imaging.fileformats.png/pngimage/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| override [GetModifyDate](../../aspose.imaging.fileformats.png/pngimage/getmodifydate/)(bool) | 检索指示资源图像最近一次修改的时间戳。此方法提供对关键元数据的访问，使应用程序能够确定图像上次被更改的时间，便于版本跟踪和内容管理。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.png/pngimage/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
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
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | 通过将此[`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) 值设为 `null` 来移除此图像实例的元数据。 |
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
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | 设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的分辨率。 |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | 将光栅图像转换为位图。此方法在 .Net7.0 及更高版本中不受支持。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

此示例展示了如何从文件加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // 将图像转换为灰度表示
    pngImage.Grayscale();

    // 保存到文件。
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### 另请参见

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png/)
* assembly [Aspose.Imaging](../../)


