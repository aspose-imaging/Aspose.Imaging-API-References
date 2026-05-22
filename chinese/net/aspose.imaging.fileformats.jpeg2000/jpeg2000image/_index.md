---
title: "类 Jpeg2000Image"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image 类。使用我们的 API 高效操作 JPEG2000 JP2 图像文件，支持多种每像素位深，并无缝处理包含关键图像信息的 XMP 元数据。具备无损压缩功能，确保在保持文件完整性的同时实现最佳图像质量，使您能够轻松按精确规格定制 JP2 图像。"
type: docs
weight: 6940
url: /zh/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
## Jpeg2000Image class

使用我们的 API 高效操作 JPEG2000 (JP2) 图像文件，支持多种每像素位深，并无缝处理包含关键图像信息的 XMP metadata。具备无损压缩功能，可确保在保持文件完整性的同时实现最佳图像质量，使您能够轻松按精确规格定制 JP2 图像。

```csharp
public sealed class Jpeg2000Image : RasterCachedImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Jpeg2000Image](jpeg2000image/#constructor)(RasterImage) | 实例化一个带有光栅图像的 `Jpeg2000Image` 类。此构造函数可从现有光栅图像创建 JPEG2000 图像，提供不同图像格式之间的无缝集成和转换。 |
| [Jpeg2000Image](jpeg2000image/#constructor_5)(Stream) | 通过提供流对象，轻松初始化 `Jpeg2000Image` 类的新实例。此构造函数简化了直接从流加载 JPEG2000 图像的过程，为处理来自各种来源的图像数据提供了灵活性和便利性。 |
| [Jpeg2000Image](jpeg2000image/#constructor_7)(string) | 通过使用要加载的图像路径初始化 `Jpeg2000Image` 类的新实例，开始使用该类。此构造函数实现对 JPEG2000 图像的轻松访问，简化了加载和处理图像文件的过程。提供文件路径后，您即可在应用程序中快速开始处理和操作 JPEG2000 图像。 |
| [Jpeg2000Image](jpeg2000image/#constructor_2)(int, int) | 创建 `Jpeg2000Image` 类的新实例，指定宽度和高度参数。此构造函数允许您以特定尺寸初始化 JPEG2000 图像，适用于需要以编程方式创建特定大小图像的场景。 |
| [Jpeg2000Image](jpeg2000image/#constructor_1)(RasterImage, int) | 使用光栅图像和每像素位数参数初始化全新的 `Jpeg2000Image` 实例。此构造函数实现对生成的 JPEG2000 图像质量和大小的精确控制，适用于定制至关重要的场景。 |
| [Jpeg2000Image](jpeg2000image/#constructor_6)(Stream, int) | 使用流加载图像并指定每像素位数参数，初始化 `Jpeg2000Image` 类的新实例。此构造函数通过允许同时指定图像数据源和所需的每像素位数，提供了灵活性，从而对图像加载过程实现更精细的控制。 |
| [Jpeg2000Image](jpeg2000image/#constructor_8)(string, int) | 通过同时提供文件路径和所需的每像素位数参数创建 `Jpeg2000Image` 类的新实例，轻松入门。此构造函数可微调图像加载过程，确保与各种图像格式和质量设置的兼容性。凭借此灵活性，您可以高效地根据具体需求管理和操作 JPEG2000 图像。 |
| [Jpeg2000Image](jpeg2000image/#constructor_4)(int, int, int) | 使用宽度、高度和位数参数创建 `Jpeg2000Image` 类的新实例。此构造函数可创建具有特定尺寸和位深的 JPEG2000 图像，为各种成像需求提供灵活性。 |
| [Jpeg2000Image](jpeg2000image/#constructor_3)(int, int, Jpeg2000Options) | 实例化一个新的 `Jpeg2000Image` 对象，提供宽度、高度和图像选项参数。此构造函数可创建具有特定尺寸和附加选项的 JPEG2000 图像，为图像生成提供灵活性。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/bitsperpixel/) { get; } | 此属性返回图像的深度，以每像素位数 (bpp) 为单位。它表示图像每个像素存储的颜色信息量。了解图像深度对于确定颜色保真度和图像质量至关重要。有了此信息，用户可以评估图像中细节和颜色丰富度的水平。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Codec](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/codec/) { get; } | 此属性检索与图像关联的 JPEG2000 编解码器。JPEG2000 编解码器负责对 JPEG2000 格式的图像数据进行编码和解码，在保持高图像质量的同时提供高效压缩。访问该编解码器可用于执行高级图像处理操作或针对特定需求优化图像压缩设置。 |
| [Comments](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/comments/) { get; set; } | 此属性允许检索或更新与图像关联的注释。注释提供关于图像内容的附加信息，如标注、描述或元数据。修改这些注释有助于对图像进行组织和分类，并向查看者或用户传达重要细节。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/fileformat/) { get; } | 检索图像文件的格式。此属性提供图像文件格式的信息。利用此属性可编程地确定图像文件的格式，从而根据文件格式进行适当的处理和操作。 |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | 获取或设置一个值，指示此 [`RasterImage`](../../aspose.imaging/rasterimage/) 实例是否具有透明颜色。 |
| override [Height](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/height/) { get; } | 此属性检索图像的像素高度。它是了解图像垂直尺寸的基本信息，有助于诸如调整大小、裁剪和渲染等各种图像操作。访问此属性可让用户确定图像的垂直尺寸，从而在应用程序中实现精确的布局和显示。 |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/horizontalresolution/) { get; set; } | 此属性允许您检索或修改 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率，单位为每英寸像素数 (PPI)。调整此分辨率会影响图像在打印或显示时的尺寸和质量。通过设置水平分辨率，用户可以针对特定输出设备或应用程序优化图像，确保获得最佳视觉效果。 |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/rawdataformat/) { get; } | 此属性检索图像的原始数据格式。它提供像素数据在内存中存储方式的信息。使用此属性可了解图像的底层数据格式，这对于颜色转换、压缩或解压缩等各种图像处理操作至关重要。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| override [RawLineSize](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/rawlinesize/) { get; } | 此属性检索原始图像数据单行的字节大小。它表示图像原始数据格式中单行像素占用的内存量。了解原始行大小对于内存分配、数据操作以及对单行图像进行处理的图像算法等任务至关重要。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | 获取图像透明颜色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/verticalresolution/) { get; set; } | 此属性提供对 [`RasterImage`](../../aspose.imaging/rasterimage/) 垂直分辨率的访问，单位为每英寸像素数 (PPI)。修改此分辨率会影响图像在打印或显示时的质量和尺寸。通过调整垂直分辨率，用户可以针对不同的输出设备或应用程序优化图像，确保最佳的视觉呈现。 |
| override [Width](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/width/) { get; } | 此属性返回图像的像素宽度。它提供关于图像尺寸的基本信息，对包括调整大小、裁剪和渲染在内的各种图像处理任务至关重要。 |
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
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | 获取资源图像最近修改的日期和时间。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/getoriginaloptions/)() | 根据原始文件设置检索图像选项。此方法有助于保持原始图像的位深度和其他参数，确保一致性并保留图像数据的完整性。访问这些选项可实现对图像的无缝处理和操作，同时保留其原始特性。例如，如果我们使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法加载一个每像素 1 位的黑白 PNG 图像并保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，可使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
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

此示例展示了如何从文件加载 JPEG2000 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // 保存为 PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../aspose.imaging.fileformats.jpeg2000/)
* assembly [Aspose.Imaging](../../)


