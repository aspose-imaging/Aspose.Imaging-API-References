---
title: "类 ApngImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Apng.ApngImage 类。针对 Animated PNG（动画可移植网络图形）图像文件格式的 API 是为希望在应用程序中集成动画内容的开发者提供的多功能解决方案。该 API 提供对帧设置的广泛控制，允许用户定义帧特定参数，包括循环时长和 PNG 文件设置。借助此功能丰富的工具，您可以轻松管理和优化 APNG 图像的显示，导入和导出图像，提升应用程序的动态和交互性。"
type: docs
weight: 1350
url: /zh/net/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

Animated PNG（Animated Portable Network Graphics）图像文件格式的 API 是面向希望在应用程序中集成动画内容的开发者的多功能解决方案。该 API 提供对帧设置的广泛控制，允许用户定义帧特定参数，包括循环时长和 PNG 文件设置。借助此功能丰富的工具，您可以轻松管理和优化 APNG 图像的显示，导入和导出图像，提升应用程序的动态和交互性。

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ApngImage](apngimage/)(ApngOptions, int, int) | 通过轻松初始化新实例，开始使用 `ApngImage` 类。非常适合希望在项目中快速高效地开始使用 ApngImage 对象的开发者。 |

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
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime/) { get; set; } | 使用此灵活属性，轻松调整创建新帧的默认帧持续时间。非常适合希望在动画中高效自定义帧时间的开发者。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat/) { get; } | 使用此便利属性，快速获取文件格式信息。非常适合需要轻松检索其 Apng 文件格式细节的开发者。 |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | 获取指示图像是否具有透明颜色的值。 |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced/) { get; } | 使用此便利属性，快速确定此 [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) 对象是否为隔行扫描。非常适合需要轻松检查 PNG 图像隔行状态的开发者。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | 获取或设置帧的 XMP 数据。 |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays/) { get; set; } | 使用此多功能属性，轻松控制动画循环的次数。非常适合希望对动画行为进行精确控制的开发者，当值等于 0 时支持无限循环。 |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount/) { get; } | 使用此属性，轻松检索图像文件的总页数。非常适合需要快速获取页数信息的开发者。 |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages/) { get; } | 使用此便利属性，轻松访问图像的各页。非常适合希望快速轻松获取单页进行操作的开发者。 |
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
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe)() | 使用此简洁方法，轻松在帧集合末尾追加新帧。非常适合希望为多帧图像动画动态扩展帧集合的开发者。新帧将根据当前图像的尺寸创建。 |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe_1)(RasterImage) | 使用此直观方法，在末尾添加新帧，轻松扩展帧集合。非常适合希望动态增强多帧图像动画的开发者。新帧的内容将从指定图像填充。 |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe_2)(RasterImage, uint) | 使用此直观方法，通过追加新帧无缝扩展帧集合。非常适合希望丰富多帧图像动画的开发者。新帧的内容将从指定图像填充。 |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage/)(RasterImage) | 使用此直观方法轻松向图像添加新页面。非常适合希望动态扩展图像文件内容的开发者。 |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness/)(int) | 使用此直观方法轻松调整图像的 *brightness*，并使用指定的亮度参数。非常适合希望动态提升或降低图像整体亮度的开发者。 |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast/)(float) | 使用此直观方法提升 [`Image`](../../aspose.imaging/image/) 的对比度，使细节更加突出。非常适合希望动态改善图像视觉清晰度和冲击力的开发者。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma/#adjustgamma)(float) | 使用此直观方法通过浮点系数对图像进行伽马校正。非常适合希望在图像中实现精确颜色控制的开发者。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma/#adjustgamma_1)(float, float, float) | 使用此直观方法对图像的红、绿、蓝通道分别使用各自的系数进行伽马校正。非常适合希望微调颜色平衡并提升图像视觉质量的开发者。 |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | 计算提取数据与原始密码之间的相似度百分比。 |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | 自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley/#binarizebradley_1)(double, int) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed/)(byte) | 使用此直观方法通过预定义阈值轻松将图像二值化。非常适合希望将图像转换为二进制形式，以便后续处理或分析的开发者。 |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu/)() | 使用此直观方法通过 Otsu 阈值法对图像进行二值化。非常适合希望自动确定最佳阈值以将图像转换为二进制形式，提升其清晰度并适合进一步分析的开发者。 |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | 缓存数据为私有。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop/#crop)(Rectangle) | 使用此直观方法轻松裁剪图像，以聚焦特定区域。非常适合希望动态优化图像构图的开发者。 |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop/#crop_1)(int, int, int, int) | 使用此直观方法在裁剪图像的同时无缝调整位移。非常适合希望对裁剪过程进行精确控制，以聚焦 Apng 图像特定区域的开发者。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 使用此直观方法轻松为当前图像应用抖动效果。非常适合希望为图像添加纹理或降低颜色带状效应的开发者。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter/)(Rectangle, FilterOptionsBase) | 使用此直观方法轻松对图像的指定矩形区域应用滤镜。非常适合希望增强或修改特定区域的开发者。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions/)(object[]) | 使用此简洁方法轻松获取默认选项。非常适合希望快速访问默认 Apng 图像设置的开发者。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate/)(bool) | 使用此友好方法快速获取资源图像最近一次修改的日期和时间。非常适合需要跟踪更改并有效管理资源的开发者。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions/)() | 使用此直观方法轻松根据原始文件设置检索选项。非常适合希望访问并利用与原始文件特性相匹配的设置的开发者。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。 |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale/)() | 使用此直观方法轻松将图像转换为灰度表示。非常适合希望将彩色图像转换为灰度，以简化可视化或分析过程的开发者。 |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe)(int) | 使用此直观方法轻松在指定位置向帧集合插入新帧。非常适合希望对多帧图像动画中帧的排列进行精确控制的开发者。新帧将根据当前图像的尺寸创建。 |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe_1)(int, RasterImage) | 在指定索引处向自身帧集合插入新帧。新帧的内容将从指定图像填充。 |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe_2)(int, RasterImage, uint) | 在指定索引处向自身帧集合插入新帧。新帧的内容将从指定图像填充。 |
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
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat/)(int) | 使用此直观方法从帧集合中移除并检索指定索引的帧。非常适合希望高效管理动画帧的开发者。 |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes/)() | 使用此直观方法通过移除所有帧来清空帧集合。非常适合希望重置或刷新动画的开发者。 |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat/)(int) | 使用此方法无缝移除帧集合中指定索引的帧。非常适合希望在多帧图像中实现简化帧管理的开发者。被删除的帧将被释放。 |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | 通过将此[`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) 值设为 `null` 来移除此图像实例的元数据。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage/)() | 使用此直观方法移除先前设置的默认图像。非常适合希望在动画中重置或清除默认图像的开发者。此后，默认图像将是自身帧集合中的第一帧（无法通过此方法删除）。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize/#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize/#resize_2)(int, int, ResizeType) | 使用此直观方法无缝调整图像大小。非常适合希望动态调整图像尺寸的开发者。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 使用此直观方法轻松在保持比例的同时调整图像高度。非常适合希望在动态调整图像大小时保持宽高比的开发者。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 使用此直观方法轻松按比例调整图像宽度。非常适合在调整尺寸时希望保持图像宽高比的开发者。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate/#rotate_1)(float, bool, Color) | 使用此直观方法轻松围绕中心旋转图像。非常适合希望动态调整图像方向的开发者。 |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip/)(RotateFlipType) | 轻松通过旋转、翻转或两者结合来操作活动帧，使用此直观方法。非常适合希望自定义图像帧方向的开发者。 |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage/)(RasterImage) | 设置在不支持 APNG 的解码器中显示的 \"默认图像\"。`ApngImage` 类使用 [`Pages`](./pages/) 的第一个元素作为默认（主）页面。 |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | 设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的分辨率。 |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | 将光栅图像转换为位图。此方法在 .Net7.0 及更高版本中不受支持。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

以下示例展示了如何将其他非动画多页格式导出为 APNG 文件格式。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // 设置默认帧持续时间
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

以下示例展示了如何导出为 APNG 文件格式。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // 导出为 APNG 动画，默认无限循环播放
    image.Save("Animation1.webp.png", new ApngOptions());
    // 设置动画循环次数
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

以下示例展示了如何从另一个光栅单页图像创建 APNG 图像。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // 可以在此处设置图像的默认帧时间：apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // 正在清理，因为图像默认包含一个帧
        apngImage.RemoveAllFrames();

        // 添加第一帧
        apngImage.AddFrame(sourceImage);

        // 添加中间帧
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // 添加最后一帧
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### 另请参见

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng/)
* assembly [Aspose.Imaging](../../)


