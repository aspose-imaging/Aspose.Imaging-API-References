---
title: "类 DjvuImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Djvu.DjvuImage 类。DjVu 文档类支持图形文件格式，并促进对扫描文档和书籍的无缝管理，将文本、绘图、图像和照片集成到单一格式中。支持多页操作，您可以高效访问唯一文档标识符、计数页数、设置活动页并检索特定文档页。该类具备调整大小、旋转、抖动、裁剪、灰度转换、伽马校正、调整和滤镜应用等功能，能够精确操作和增强 DjVu 图像，以轻松且精准地满足多样化的应用需求。"
type: docs
weight: 2530
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/
---
## DjvuImage class

DjVu 文档类支持图形文件格式，并促进对扫描文档和书籍的无缝管理，将文本、图稿、图像和照片集成到单一格式中。支持多页操作，您可以高效地访问唯一的文档标识符、统计页数、设置活动页并检索特定文档页。该类具备调整大小、旋转、抖动、裁剪、灰度转换、伽马校正、调节以及滤镜应用等功能，使您能够精确地操作和增强 DjVu 图像，以轻松且精准地满足多样化的应用需求。

```csharp
public sealed class DjvuImage : RasterCachedMultipageImage, INotifyPropertyChanged
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DjvuImage](djvuimage/#constructor)(Stream) | 通过使用 Stream 参数初始化 `DjvuImage` 类的新实例，开始使用 DjVu 图像。非常适合希望将 DjVu 图像处理无缝集成到项目中的开发者。 |
| [DjvuImage](djvuimage/#constructor_1)(Stream, LoadOptions) | 使用此构造函数无缝开始使用 DjVu 图像，该构造函数使用 Stream 和 LoadOptions 参数初始化 `DjvuImage` 类的新实例。非常适合希望在保持简洁高效的同时，对 DjVu 图像加载选项进行精确控制的开发者。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.djvu/djvuimage/activepage/) { get; set; } | 通过使用此属性访问或设置当前活动页，浏览您的 DjVu 文档。可无缝在页面之间切换，以聚焦特定内容并提升文档阅读体验。 |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | 获取图像的每像素位数。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [DjvuPages](../../aspose.imaging.fileformats.djvu/djvuimage/djvupages/) { get; } | 使用此属性快速检索 DjVu 文档中包含的所有页面。通过轻松访问和管理 DjVu 文件中的各个页面，简化文档处理工作流。借助便捷的页面检索，提高效率并优化任务。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.djvu/djvuimage/fileformat/) { get; } | 获取与 DjVu 图像文件关联的文件格式信息。快速确定文件格式，以便在工作流中实现无缝集成。 |
| [FirstPage](../../aspose.imaging.fileformats.djvu/djvuimage/firstpage/) { get; } | 使用此属性访问 DjVu 文档的首页。快速检索首页，以高效开始查看或处理文档。 |
| override [HasAlpha](../../aspose.imaging.fileformats.djvu/djvuimage/hasalpha/) { get; } | 快速判断 DjVu 图像文件是否包含 Alpha 通道。通过检查图像中的透明信息，简化工作流。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | 获取指示图像是否具有透明颜色的值。 |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| [Identifier](../../aspose.imaging.fileformats.djvu/djvuimage/identifier/) { get; } | 获取文档的唯一标识符 |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| [LastPage](../../aspose.imaging.fileformats.djvu/djvuimage/lastpage/) { get; } | 使用此属性检索 DjVu 文档的最后一页。轻松快速访问末页，以进行查看或处理。 |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | 获取或设置帧的 XMP 数据。 |
| [NextPage](../../aspose.imaging.fileformats.djvu/djvuimage/nextpage/) { get; } | 通过使用此便捷属性访问下一页，浏览 DjVu 文档。快速向前移动，以进行文档查看或处理任务。 |
| override [PageCount](../../aspose.imaging.fileformats.djvu/djvuimage/pagecount/) { get; } | 使用此属性检索 DjVu 图像集合的总页数。非常适合快速评估存储在 DjVu 格式中的文档或书籍的规模。通过准确的页数信息提升工作流效率。 |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.djvu/djvuimage/pages/) { get; } | 使用此属性访问 DjVu 图像集合的各个页面。通过直接访问每页，简化对存储在 DjVu 格式中的文档或书籍的导航和操作。通过轻松的页面检索提升工作流效率。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [PreviousPage](../../aspose.imaging.fileformats.djvu/djvuimage/previouspage/) { get; } | 通过使用此便捷属性访问上一页，快速向后移动 DjVu 文档的查看或处理任务。轻松高效地在文档中导航。 |
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
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument/#loaddocument)(Stream) | 使用此方法加载 DjVu 文档。通过快速访问并导入 DjVu 文件到您的应用程序，简化流程。 |
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument/#loaddocument_1)(Stream, LoadOptions) | 使用此方法并提供 stream 和 loadOptions 参数来导入您的 DjVu 文档。通过快速访问并导入 DjVu 文件到您的应用程序，简化您的流程，提供灵活性和自定义选项以满足您的需求。 |
| override [AdjustBrightness](../../aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness/)(int) | 使用指定参数调整图像的 *brightness*，提供对亮度水平的控制以获得最佳视觉清晰度。此方法可以增强或降低图像的整体亮度，允许进行细微调整以实现所需的光照效果。通过调节亮度，用户可以优化图像可见性并提升细节再现，从而改善观看体验。 |
| override [AdjustContrast](../../aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast/)(float) | 使用此方法增强 [`Image`](../../aspose.imaging/image/) 对比度，以提升视觉清晰度并突出细节，该方法调整亮部和暗部之间的亮度差异。通过微调对比度水平，用户可以获得更鲜明、更有冲击力的图像，提升整体图像质量并最大化细节可见性。此调整有助于展现颜色和纹理的微妙差别，产生更具动感和视觉吸引力的图像。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/#adjustgamma)(float) | 伽马校正，特别针对红、绿、蓝通道，涉及分别调整每个颜色分量的亮度。通过对 RGB 通道应用不同的伽马系数，您可以微调图像的整体亮度和对比度。此技术确保颜色表现准确，并提升图像在不同显示设备上的视觉质量。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/#adjustgamma_1)(float, float, float) | 对图像进行伽马校正时，可为红、绿、蓝通道设置可自定义的参数，从而实现对色彩平衡和亮度的精确调节。此方法通过微调颜色表现提升图像质量，确保在不同显示设备上的最佳渲染。对各通道的伽马值进行调整可改善色彩平衡和视觉吸引力。 |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | 计算提取数据与原始密码之间的相似度百分比。 |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | 自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/#binarizebradley_1)(double, int) | 使用 Bradley 自适应阈值算法结合积分图阈值的二值化方法会根据局部邻域为每个像素计算局部阈值。它能够适应图像中光照的变化，适用于光照不均的图像。通过使用积分图计算阈值，可高效处理大范围邻域，使其适用于实时应用。该技术常用于文档处理、OCR（光学字符识别）和图像分割任务，在这些场景中准确的二值化对后续分析至关重要。 |
| override [BinarizeFixed](../../aspose.imaging.fileformats.djvu/djvuimage/binarizefixed/)(byte) | 使用预定义阈值的二值化将复杂图像简化为二进制表示，像素根据其强度与指定阈值的比较被归类为黑或白。此技术常用于图像处理，以提升清晰度、简化分析，并为后续处理步骤（如光学字符识别（OCR））准备图像。通过应用固定阈值，您可以快速将灰度图像转换为二进制形式，使其更易于解释和提取有意义的信息。 |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/)() | 使用 Otsu 阈值的二值化是一种基于图像直方图自动计算最佳阈值的技术。它通过最小化类内方差将图像划分为前景和背景。Otsu 方法在将图像分割为二进制形式时被广泛使用，尤其在像素强度分布呈双峰或多峰时。该方法对目标检测、图像分割和特征提取等任务有益，因为在这些任务中前景与背景的准确划分至关重要。 |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [CacheData](../../aspose.imaging.fileformats.djvu/djvuimage/cachedata/)() | 私有缓存数据以优化性能，减少对外部来源的重复数据检索。此方法还能帮助节约资源，尤其在数据访问频繁或资源受限的场景中。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop/#crop)(Rectangle) | \"Crop\"裁剪图像以聚焦特定细节或去除不需要的元素，提升构图和视觉冲击力。无论是为社交媒体调整照片、创建网站横幅，还是设计印刷材料，此工具都能帮助您以精确和清晰的方式完善图像。 |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop/#crop_1)(int, int, int, int) | 带位移的 Crop 允许您精确调整图像中裁剪区域的位置和尺寸。此功能在优化构图、对齐元素以及突出视觉焦点方面极为宝贵。通过在裁剪过程中加入位移，您可以轻松实现像素级的精确度，并微调图像的框架。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging.fileformats.djvu/djvuimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | \"Dither\"功能对图像应用抖动效果，通过降低条带现象和改善色彩过渡来提升视觉质量。无论您从事数字艺术、摄影还是平面设计项目，此功能都能为图像增添专业感，使其看起来更平滑、更精致。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| override [Filter](../../aspose.imaging.fileformats.djvu/djvuimage/filter/)(Rectangle, FilterOptionsBase) | 在图像的指定矩形区域内应用滤镜，以增强或修改其外观。通过针对特定区域，此方法可进行精确调整，如模糊、锐化或应用艺术效果，以实现期望的视觉效果。对选定区域的滤镜进行微调，使用户能够自定义图像美感、提升清晰度，并创建符合个人偏好的艺术效果。 |
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
| override [Grayscale](../../aspose.imaging.fileformats.djvu/djvuimage/grayscale/)() | 灰度转换将图像转换为黑白表示，每个像素的强度由介于黑到白之间的单一数值表示。此过程去除颜色信息，生成单色图像。灰度图像常用于颜色非必需或追求简洁的场景，如文档扫描、打印以及某些图像分析。 |
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
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize/#resize_1)(int, int, ImageResizeSettings) | 在必要时应用额外设置，将图像调整为指定的宽度和高度。此方法使用户能够在保持所需属性（如宽高比、图像质量和压缩设置）的同时调整图像尺寸。通过提供灵活的缩放选项，用户可以根据具体需求定制图像，并优化其在各种应用和平台上的呈现效果。 |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize/#resize_2)(int, int, ResizeType) | 使用 `Resize` 方法对图像进行缩放，提供一种简单且有效的方式根据需求调整图像尺寸。这一多功能特性使您能够轻松将图像缩放至所需大小，提升其在各种平台和应用中的可用性。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | `ResizeHeightProportionally` 方法允许您在保持宽高比的前提下调整图像的高度。这确保图像保持比例，防止失真并保持视觉完整性。无论是为网页、移动应用还是印刷媒体优化图像，此方法都能确保图像在不同平台和设备上呈现最佳效果。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | `ResizeWidthProportionally` 方法提供了一种便捷的解决方案，在保持宽高比的同时调整图像宽度。通过按比例调整宽度，您可以确保图像在不同设备和屏幕尺寸上保持视觉吸引力和一致性，提升其在各种场景中的多样性和可用性。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.djvu/djvuimage/rotate/#rotate_1)(float, bool, Color) | 使用 RasterCachedMultipageImage 类的 Rotate 方法围绕中心旋转图像。此便捷功能让您轻松调整图像方向，同时保持中心位置，提升图像操作能力。 |
| override [RotateFlip](../../aspose.imaging.fileformats.djvu/djvuimage/rotateflip/)(RotateFlipType) | `RotateFlip` 方法为图像提供多样的操作选项，允许您对活动帧独立进行旋转、翻转或两者兼施。无论是编辑照片、创建图形还是提升数字艺术，此方法都能对图像的方向和构图提供精确控制，确保轻松高效地实现您的创意构想。 |
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

## 事件

| 名称 | 描述 |
| --- | --- |
| event [PropertyChanged](../../aspose.imaging.fileformats.djvu/djvuimage/propertychanged/) | 当属性值更改时触发。 |

## 示例

此示例展示了如何从文件流加载 DJVU 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // 将每个页面保存为单独的 PNG 图像。
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // 根据页码生成文件名。
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### 另请参见

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../aspose.imaging.fileformats.djvu/)
* assembly [Aspose.Imaging](../../)


