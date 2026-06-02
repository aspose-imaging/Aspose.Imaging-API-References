---
title: "类 GifImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Gif.GifImage 类。该 API 用于图形交换格式（GIF）图像文件，为开发者提供处理压缩光栅图像和动画 GIF 的多功能工具。提供的功能包括 XMP 元数据处理、颜色调色板设置、背景和透明颜色控制、不透明度设置、大小调整、裁剪、滤镜应用、伽马校正、对比度调节、灰度转换以及转换为其他格式。此 API 使得在广泛的应用场景中对 GIF 图像进行无缝操作和增强成为可能。"
type: docs
weight: 6800
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

针对图形交换格式（GIF）图像文件的 API 为开发者提供了处理压缩光栅图像和动画 GIF 的多功能工具。它提供了 XMP 元数据处理、颜色调色板设置、背景色和透明色控制、不透明度设置、尺寸调整、裁剪、滤镜应用、伽马校正、对比度调节、灰度转换以及转换为其他格式等功能。该 API 使得在各种应用中对 GIF 图像进行无缝操作和增强成为可能。

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GifImage](gifimage/#constructor)(GifFrameBlock) | 使用 `GifImage` 构造函数创建 GIF 图像变得轻而易举。只需提供 firstFrame 参数，即可进入动态视觉传达的世界。 |
| [GifImage](gifimage/#constructor_1)(GifFrameBlock, IColorPalette) | 使用指定的首帧和全局调色板参数初始化新的 `GifImage` 对象。快速开始管理 GIF 图像，确保通过可自定义设置实现准确呈现和最佳效果。 |
| [GifImage](gifimage/#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | 使用 `GifImage` 构造函数轻松入门。通过此简便方法，您可以轻松创建动画 GIF。只需提供 firstFrame、globalPalette、paletteColorResolution、aspectRatio 等参数，即可让您的视觉作品栩栩如生。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe/) { get; set; } | 使用此属性管理和操作帧，实现对 GIF 图像中活动帧的平滑导航和修改。 |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor/) { get; set; } | 使用此属性管理 GIF 图像的背景颜色。您可以设置或获取背景颜色，以确保一致性并提升视觉吸引力。 |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex/) { get; set; } | 使用此属性控制 GIF 图像的背景颜色索引。设置或获取索引，以保持一致性或实现所需的视觉效果。 |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | 获取图像的每像素位数。 |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks/) { get; } | 通过此属性无缝访问 GIF 块，便于轻松检索和操作图像底层数据结构。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat/) { get; } | 使用此属性轻松获取文件格式。它是识别文件格式的首选来源。无缝集成到您的工作流中，提供重要信息，毫不费力。 |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha。 |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor/) { get; } | 此属性决定 GIF 图像是否包含背景颜色。如果为 true，则表示图像包含背景颜色。 |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer/) { get; set; } | 使用此属性管理 GIF 文件中 trailer 的存在。无论是检查 trailer 是否存在还是设置其存在性，此属性都简化了操作。通过此直观功能保持 GIF 文件的结构化和合规性。 |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor/) { get; set; } | 确定 GIF 图像的活动帧是否包含透明颜色。此属性提供了一种便捷的方式来检查图像内部的透明度。 |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity/) { get; } | 获取图像中活动帧的不透明度，了解其透明程度。此属性对于理解活动帧的透明或不透明程度特别有用。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced/) { get; } | 确定图像是否为交错显示，这会影响加载时的呈现。此属性提供对图像渲染行为的洞察，对优化加载策略和提升整体观看体验至关重要。 |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted/) { get; set; } | 使用此属性控制 GIF 图像中调色板的排序。无论是检查调色板是否已排序还是设置排序行为，此属性都提供了一种直接的方式来管理 GIF 文件中的调色板组织。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount/) { get; set; } | 使用此属性轻松获取循环计数。如果您的 GIF 图像包含循环信息，此属性可快速获取循环计数，使您能够无缝管理 GIF 文件中的循环行为。 |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | 获取或设置帧的 XMP 数据。 |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount/) { get; } | 检索图像中包含的页面总数，使用此简洁属性。非常适合快速评估图像内容的范围。 |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages/) { get; } | 通过此便利属性获取图像中的页面，允许无缝导航并根据需要操作各个页面。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits/) { get; set; } | 使用此属性管理 GIF 图像的调色板颜色分辨率。调整用于表示调色板颜色的位数，提供对色深和图像质量的精细控制。 |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio/) { get; set; } | 使用此属性管理 GIF 图像的像素宽高比。设置或检索宽高比，以确保渲染准确并保持视觉保真度。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor/) { get; } | 检索 GIF 图像中活动帧的透明颜色。此属性允许您访问当前活动帧中被指定为透明的特定颜色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | 获取图像宽度。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock/)(IGifBlock) | 添加新的 GIF 块可让您在图像中包含额外数据。此方法使您能够向 GIF 图像追加自定义块，这些块可以包含各种类型的信息。 |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage/)(RasterImage) | 将新页面无缝合并到现有图像中，增强其内容并扩展其范围。此方法为图像集合添加额外内容，促进图像管理和构图的创造性与灵活性。 |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness/)(int) | 根据指定的 *brightness* 参数调整图像的亮度。此方法统一地修改整幅图像的亮度，增强或降低整体光照以实现所需效果。 |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast/)(float) | 调整图像的对比度，增强或降低像素之间的亮度差异。此方法修改图像的整体色调范围，使暗部更暗、亮部更亮，以提升视觉清晰度和细节。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma/#adjustgamma)(float) | 通过应用伽马校正提升图像质量。此方法调整图像的颜色伽马以获得最佳视觉清晰度。它修改每个像素的伽马值，从而改善颜色呈现和整体图像外观。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma/#adjustgamma_1)(float, float, float) | 图像的伽马校正对像素值进行非线性调整，根据红、绿、蓝通道的指定系数增强或降低亮度。此方法有助于微调图像的色彩平衡和亮度，提升整体外观和视觉质量。 |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | 计算提取数据与原始密码之间的相似度百分比。 |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | 自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。 |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley/#binarizebradley)(double) | 使用 Bradley 自适应阈值算法结合积分图阈值化对图像进行二值化，是将灰度图像转换为二值图像的方法。该算法根据指定窗口内周围像素的平均强度为每个像素计算局部阈值。通过根据局部像素强度自适应地调整阈值，Bradley 方法能够有效处理图像中的光照和对比度变化。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double, int) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed/)(byte) | 使用预定义阈值对图像进行二值化，将灰度或彩色图像转换为二值图像，根据像素强度是否超过指定阈值，将每个像素分类为黑或白。 |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu/)() | 使用 Otsu 阈值法对图像进行二值化是一种自动确定将灰度图像转换为二值图像的最佳阈值的方法。Otsu 阈值算法计算使前景和背景两类像素强度的类内方差最小的阈值。当最佳阈值未知且需要根据图像直方图自适应确定时，此技术尤为有用。 |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | 缓存数据为私有。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks/)() | 清除所有 GIF 块会移除图像中存储的任何现有数据。此操作有效地将图像重置为空状态，删除之前添加的所有块。当您需要以全新状态创建或修改 GIF 图像时，请使用此方法。 |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop/#crop)(Rectangle) | 使用指定的矩形区域裁剪图像。此操作去除图像的外部部分，仅保留矩形定义的选定区域。 |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop/)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 对当前图像应用抖动处理。此过程通过减少颜色带状现象并改善颜色过渡来提升图像质量，使外观更平滑。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter/)(Rectangle, FilterOptionsBase) | 对图像指定区域应用特定滤镜，提升其视觉质量或按需改变外观。此方法在定义的矩形内有选择地处理像素，允许进行针对性调整，同时保持周围图像数据的完整性。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | 获取资源图像最近修改的日期和时间。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions/)() | 检索基于原始文件设置的选项，对于在图像处理和操作中保持保真度和一致性至关重要。此方法允许将文件特定参数无缝集成到后续操作中，确保渲染准确并遵循图像固有特性。这有助于保持原始图像的位深和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用[`Save`](../../aspose.imaging/datastreamsupporter/save/)方法保存，输出的 PNG 图像将是每像素 8 位。为避免此情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二参数传递给[`Save`](../../aspose.imaging/image/save/)方法。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。 |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale/)() | 将图像转换为灰度表示会通过去除颜色信息而保留亮度，将彩色图像转换为灰度版本。此过程将图像简化为灰度阴影，适用于打印、文档处理和灰度分析等各种应用。 |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock/)(int, IGifBlock) | 插入新的 GIF 块允许您在图像的特定位置添加自定义数据。此方法使您能够在 GIF 图像中将自定义块放置在所需位置，提供组织和结构化图像数据的灵活性。 |
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
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks/)() | 按照 GIF 规范对 GIF 块进行排序可确保 GIF 布局正确并符合标准。此过程涉及按规范定义的正确顺序排列块。此外，还可能需要移除某些[`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/)实例，这些实例对最终布局并非必需。遵循 GIF 规范后，生成的图像将结构正确并兼容 GIF 查看应用程序。 |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock/)(IGifBlock) | 移除 GIF 块会从图像中删除特定数据，提供清理或修改图像结构的能力。此方法使您能够删除不需要的块，优化 GIF 图像的存储效率。使用此功能可在保持图像完整性和质量的同时，消除过时信息。 |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | 通过将此[`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) 值设为 `null` 来移除此图像实例的元数据。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize/#resize_1)(int, int, ImageResizeSettings) | 调整此[`Image`](../../aspose.imaging/image/)实例的大小。 |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize/#resize_2)(int, int, ResizeType) | 调整此[`Image`](../../aspose.imaging/image/)实例的大小。 |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe/)(int, int, ResizeType) | 在调整图像大小时考虑 GIF 每页的全部帧，从而防止潜在伪影的出现。此方法对于保持图像的完整性和质量至关重要，尤其在处理动画 GIF 或帧序列时。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional/)(int, int, ResizeType) | 比例缩放在调整图像大小的同时保持图像的宽高比，确保图像不会出现拉伸或失真。此方法按比例调整图像大小，宽度和高度以相同的比例进行缩放。比例缩放将根据 *newWidth*/width 和 *newHeight*/height 的比例来调整每帧的大小。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate/#rotate_1)(float, bool, Color) | 此方法围绕图像的中心点旋转图像。通过指定旋转角度，您可以顺时针或逆时针旋转图像，以实现所需的方向。此旋转有助于在不失真内容的情况下调整图像的呈现或对齐。 |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip/)(RotateFlipType) | 仅对活动帧执行旋转、翻转或两者。此操作仅对图像当前活动的帧应用变换，保持序列中其他帧的完整性。 |
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
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime/)(ushort) | 以毫秒为单位调整每帧的持续时间，确保整个图像序列的时间一致。此方法统一设置每帧的显示时间，从而精确控制动画速度。更改此值将重置所有帧的延迟。 |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | 设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的分辨率。 |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | 将光栅图像转换为位图。此方法在 .Net7.0 及更高版本中不受支持。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

基于时间间隔导出 GIF 图像的部分动画。

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

此示例展示了如何创建 GIF 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 GIF 帧块。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // 将整个块填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

使用单页光栅图像创建多页 GIF 图像。

```csharp
[C#]

static void Main(string[] args)
{
    // 加载帧
    var frames = LoadFrames("Animation frames").ToArray();

    // 使用第一帧创建 GIF 图像
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // 使用 AddPage 方法向 GIF 图像添加帧
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // 保存 GIF 图像
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### 另请参见

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif/)
* assembly [Aspose.Imaging](../../)


