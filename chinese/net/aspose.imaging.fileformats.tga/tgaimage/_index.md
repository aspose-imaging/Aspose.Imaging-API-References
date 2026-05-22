---
title: "类 TgaImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Tga.TgaImage 类。使用我们针对 TARGA Truevision Advanced Raster Adapter 格式定制的 API 操作 TGA 栅格图像文件，实现无缝加载和自定义。可以轻松更新公共属性，如作者、时间戳、图像 ID 和软件版本，同时使用各种每像素位数设置、Alpha 通道和颜色透明度。此外，您还可以将 TGA 图像导出为其他流行的栅格格式，确保项目的兼容性。"
type: docs
weight: 7690
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

使用我们的 API 操作 TGA 栅格图像文件，该 API 针对 TARGA（Truevision Advanced Raster Adapter）格式进行定制，实现无缝加载和自定义。可以轻松更新作者、时间戳、图像 ID 和软件版本等公共属性，同时使用不同的每像素位数设置、Alpha 通道和颜色透明度。此外，您还可以将 TGA 图像导出为其他流行的栅格格式，确保项目的兼容性。

```csharp
public class TgaImage : RasterCachedImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TgaImage](tgaimage/#constructor)(RasterImage) | 通过提供栅格图像对象创建 `TgaImage` 类的新实例。此构造函数促进将现有栅格图像直接集成到 TGA 图像格式中，简化转换过程，以提升软件系统的兼容性。 |
| [TgaImage](tgaimage/#constructor_1)(Stream) | 使用流加载图像来初始化 `TgaImage` 类的新实例。此构造函数允许从流中无缝集成图像数据，促进在软件应用中高效处理和操作 TGA 图像。 |
| [TgaImage](tgaimage/#constructor_2)(string) | 使用提供的文件路径加载图像内容，初始化一个新的 `TgaImage` 对象。此构造函数高效地初始化图像实例，允许无缝访问 TGA 图像文件，简化在应用工作流中的集成。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AuthorComments](../../aspose.imaging.fileformats.tga/tgaimage/authorcomments/) { get; set; } | 检索或设置图像作者提供的注释。这些注释通常包含有价值的信息，如描述、标注或关于图像的其他上下文。通过访问或修改 Author Comments 属性，开发者可以增强图像的元数据，为用户提供有关内容或创作的有价值的洞察和背景。该字段为 ASCII，长度为 324 字节，组织为四行每行 80 个字符，随后跟随一个空字符终止符。 |
| [AuthorName](../../aspose.imaging.fileformats.tga/tgaimage/authorname/) { get; set; } | 检索或设置与图像关联的作者姓名。此属性允许开发者访问或修改作者姓名元数据，提供有关图像创建者的有价值信息。通过使用 Author Name 属性，用户可以轻松识别图像的创作者或贡献者，提升整体元数据并为观众提供有价值的上下文。该字段总计 40 个 ASCII 字符用于存放姓名。如果使用该字段，应包含创建图像的人的姓名（作者）。 |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/backgroundcolor/) { get; set; } | 检索或设置图像的背景颜色。此属性允许您指定用于图像背景的颜色，确保一致性并提升视觉呈现。它在图像显示在不同颜色背景或将图像渲染到其他画布时尤为有用。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bitsperpixel/) { get; } | 检索每像素位数值，提供关于图像色彩深度的关键信息。此属性是了解图像细节层次和色彩丰富度的重要指标，有助于开发者优化处理算法和资源分配，以实现高效的图像操作和渲染任务。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [BytesPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bytesperpixel/) { get; } | 获取每像素字节数值，表示图像中每个像素占用的内存量。此属性是内存管理和优化的关键指标，帮助开发者高效分配资源并处理图像数据。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [DateTimeStamp](../../aspose.imaging.fileformats.tga/tgaimage/datetimestamp/) { get; set; } | 获取或设置日期/时间戳。此字段定义图像保存的日期和时间值。尽管操作系统通常会为文件添加时间戳，但提供此功能是因为操作系统在复制文件时可能会更改时间戳。使用此区域，可确保日期和时间记录保持未修改的区域。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.tga/tgaimage/fileformat/) { get; } | 获取此 `TgaImage` 实例所表示的图像文件格式的关键信息。了解文件格式对于兼容性检查和确保在软件系统中无缝集成至关重要，从而实现高效的图像处理和操作。 |
| [GammaValueDenominator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/) { get; } | 检索伽马值的分母部分，这是决定图像颜色表现的关键因素。对于缺少伽马校正的图像，该值应为 1.0，以确保准确的颜色渲染。理解并利用此参数对于保持色彩保真度和实现精确的图像可视化至关重要。 |
| [GammaValueNumerator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator/) { get; } | 获取 gamma 值的分子部分，这对于图像中的准确颜色表示至关重要。在未进行 gamma 校正的图像中，此值应为 1.0。理解并利用此值对于保持颜色保真度和确保图像渲染的准确性至关重要。 |
| override [HasAlpha](../../aspose.imaging.fileformats.tga/tgaimage/hasalpha/) { get; } | 检索一个布尔值，指示 `TgaImage` 是否包含 alpha 通道，以实现透明效果。此属性提供处理图像合成和渲染的必要信息，帮助开发者实现多样的视觉效果和合成操作。 |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/hasbackgroundcolor/) { get; set; } | 获取或设置一个值，指示图像是否包含背景颜色。此属性用于确定图像是否具有与前景内容分离的明确背景颜色。它使您能够根据是否存在背景颜色来自定义图像处理或渲染。 |
| [HasColorMap](../../aspose.imaging.fileformats.tga/tgaimage/hascolormap/) { get; } | 检索此 `TgaImage` 实例是否包含颜色映射。了解颜色映射的存在对于准确解释和操作图像的颜色数据至关重要。 |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/hastransparentcolor/) { get; set; } | 获取或设置一个布尔值，指示图像是否包含透明颜色。此属性对于识别图像是否支持透明度至关重要，帮助您实现适当的透明相关操作，如混合、合成或遮罩。 |
| override [Height](../../aspose.imaging.fileformats.tga/tgaimage/height/) { get; } | 获取由此 `TgaImage` 实例封装的图像高度。此属性为开发者提供有关图像垂直尺寸的关键细节，便于在软件解决方案中无缝集成和操作图像。 |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| [ImageId](../../aspose.imaging.fileformats.tga/tgaimage/imageid/) { get; set; } | 获取或设置与图像关联的唯一标识符。此 ID 用作在系统或应用程序中识别和区分图像的参考点。通过设置或检索 Image ID，您可以有效管理和跟踪图像，促进有序的图像管理和检索过程。 |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsGrayScale](../../aspose.imaging.fileformats.tga/tgaimage/isgrayscale/) { get; } | 获取一个布尔值，指示 `TgaImage` 是否表示灰度图像。此属性对于区分彩色图像和灰度图像至关重要，帮助开发者根据图像的颜色特性采用适当的处理和渲染技术。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| [JobNameOrId](../../aspose.imaging.fileformats.tga/tgaimage/jobnameorid/) { get; set; } | 获取或设置与图像关联的作业名称或 ID。此属性使您能够访问或修改与图像相关的特定作业或项目的元数据。通过使用作业名称/ID 属性，用户可以轻松识别图像所属的项目或任务，促进在更大工作流或项目中对图像资产的组织和管理。 |
| [JobTime](../../aspose.imaging.fileformats.tga/tgaimage/jobtime/) { get; set; } | 获取或设置指示图像关联的作业时间的时间戳。此属性允许开发者访问或修改与特定作业或项目相关的时间元数据。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [PixelAspectRatioDenominator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator/) { get; } | 检索像素纵横比的分母部分，这是决定图像中像素视觉比例的关键因素。此值对于在各种图像渲染和处理操作中保持准确的像素表示和纵横比至关重要，确保高质量的视觉输出。 |
| [PixelAspectRatioNumerator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator/) { get; } | 检索像素纵横比的分子部分，它影响图像中像素的视觉比例。理解并操作此值对于在图像渲染和处理过程中实现准确的像素表示和纵横比至关重要。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SoftwareId](../../aspose.imaging.fileformats.tga/tgaimage/softwareid/) { get; set; } | 管理与图像关联的软件标识（ID），最多可包含 40 个 ASCII 字符。此属性用于唯一标识用于创建或处理图像的软件，提供有价值的元数据以供组织和信息用途。 |
| [SoftwareVersion](../../aspose.imaging.fileformats.tga/tgaimage/softwareversion/) { get; set; } | 获取或设置与图像关联的软件版本。版本字符串的接受长度通常为 3 到 4 个字符。此属性有助于跟踪用于创建或操作图像的软件，并可为图像处理和兼容性检查提供有价值的上下文。 |
| [SoftwareVersionLetter](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionletter/) { get; set; } | 获取或设置与图像关联的软件版本的字母部分。此属性表示软件版本字符串中的附加细节，可用于更细致的版本区分。 |
| [SoftwareVersionNumber](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionnumber/) { get; set; } | 获取或设置与图像关联的软件版本的数字部分。此属性表示软件版本字符串的数值部分，提供有关用于创建或修改图像的软件版本的重要信息。 |
| override [TransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/transparentcolor/) { get; set; } | 获取或设置与图像关联的关键颜色。此属性允许您访问或修改指定为特定图像处理任务或效果的关键颜色。使用关键颜色属性可让用户执行基于颜色的操作，如色度键控或颜色替换，增强图像操作能力和创意可能性。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| override [Width](../../aspose.imaging.fileformats.tga/tgaimage/width/) { get; } | 检索此 `TgaImage` 实例所表示图像的宽度。此属性为开发者提供有关图像尺寸的必要信息，促进在软件应用中进行各种图像操作和处理任务。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |
| [XOrigin](../../aspose.imaging.fileformats.tga/tgaimage/xorigin/) { get; set; } | 获取或设置图像左下角在显示设备上定位时的绝对水平坐标，该设备的原点位于屏幕左下角（例如 TARGA 系列）。 |
| [YOrigin](../../aspose.imaging.fileformats.tga/tgaimage/yorigin/) { get; set; } | 获取或设置图像左下角在显示设备上定位时的绝对垂直坐标，该设备的原点位于屏幕左下角（例如 TARGA 系列）。 |

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
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone/#clone)() | 生成当前实例的副本，创建一个克隆原始所有属性和特性的新对象。此方法有助于创建完全相同的拷贝，确保数据完整性并在不影响原对象的情况下保留当前实例的状态。 |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone/#clone_1)(TgaImage) | 复制另一个 `TgaImage` 对象的属性，创建一个具有相同属性的新实例。此操作确保数据完整性，并在不更改源对象的情况下实现图像属性的复制。 |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop/#crop)(Rectangle) | 将图像裁剪到指定区域。此方法允许您定义图像中要保留的矩形区域，丢弃其余部分。此操作有助于聚焦图像的特定内容或去除不需要的部分。 |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop/#crop_1)(int, int, int, int) | 通过指定左、右、上、下边界的偏移量来裁剪图像。此方法允许您沿水平和垂直轴独立移动边界来修剪图像。通过调整这些偏移量，您可以精确控制保留的图像部分，有效地将其裁剪到所需尺寸。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动处理。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedimage/embeddigitalsignature/)(string) | 使用隐写技术将基于提供的密码的数字签名嵌入图像中。 |
| override [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals/#equals_1)(object) | 该方法在当前 `TgaImage` 实例与作为参数提供的另一个对象之间执行相等性比较。具体而言，它评估当前图像的属性是否与第二个对象的属性匹配，以帮助在图像处理工作流中确定它们的等价性用于比较。 |
| [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals/#equals)(TgaImage) | 在相等比较中，方法评估当前 `TgaImage` 实例是否等于作为参数提供的第二幅图像。此操作有助于确定两个 TGA 图像是否相同，支持图像处理和比较任务。 |
| virtual [Filter](../../aspose.imaging/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 过滤指定的矩形。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| override [GetHashCode](../../aspose.imaging.fileformats.tga/tgaimage/gethashcode/)() | 检索当前实例的哈希码。但需注意，此哈希码可能不适合作为键使用，特别是因为 TgaImage 类的实例不是不可变的。 |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | 获取资源图像最近修改的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
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
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize/#resize_1)(int, int, ImageResizeSettings) | 在保持所需尺寸和宽高比的同时调整图像大小。通过自定义图像设置，您可以有效地调整图像大小，同时确保最佳的视觉质量并兼容不同的显示设备或应用程序。 |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize/#resize_2)(int, int, ResizeType) | 使用指定的缩放类型调整图像大小，该类型决定了缩放操作的执行方式。此方法在根据不同算法或技术对图像进行缩放时提供灵活性。通过选择合适的缩放类型，您可以根据具体需求或偏好在图像质量和计算效率之间实现所需的平衡。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.tga/tgaimage/rotate/#rotate_1)(float, bool, Color) | 围绕图像中心按指定角度旋转图像，同时保持缩放比例并保留背景颜色。此方法允许精确的图像操作，确保旋转保持视觉平衡并与指定的背景颜色保持一致。它非常适合需要围绕中心进行精确旋转的任务，例如方向校正或艺术调整。 |
| override [RotateFlip](../../aspose.imaging.fileformats.tga/tgaimage/rotateflip/)(RotateFlipType) | “RotateFlip” 方法启用对图像的旋转和翻转操作。它提供多功能的图像方向操作，允许用户根据需求执行旋转和翻转，从而促进软件应用中的高效图像处理任务。 |
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
| [operator ==](../../aspose.imaging.fileformats.tga/tgaimage/op_equality/) | 在两个 TGA 图像之间执行相等比较，考虑比较过程中涉及的第一幅和第二幅图像。此方法有助于直接评估图像相等性，确保在图像处理工作流中进行准确的分析和决策。 |
| [operator !=](../../aspose.imaging.fileformats.tga/tgaimage/op_inequality/) | 在两个 TGA 图像之间进行不相等比较，评估比较中涉及的第一幅和第二幅图像。此方法有助于识别图像之间的差异或不一致，从而在图像处理任务中实现精确的分析和决策。 |

## 示例

将 JPG 图像保存为 TGA 图像。

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

加载 PNG 图像，将其转换为 TgaImage 并保存为 TGA 图像。

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

更新已加载 TGA 图像的公共属性。

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

获取已加载 TGA 图像的公共属性的值。

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### 另请参见

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga/)
* assembly [Aspose.Imaging](../../)


