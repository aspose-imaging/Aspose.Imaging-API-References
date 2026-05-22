---
title: "类 BmpImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Bmp.BmpImage 类。您可以轻松处理 Bitmap BMP 和设备无关位图 DIB 文件，促进对光栅图像的高效操作和处理。执行各种图像操作时，此 API 简化工作流程，为开发人员提供可靠的工具包，以在其软件应用中使用 BMP 和 DIB 格式。"
type: docs
weight: 1430
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/
---
## BmpImage class

您可以轻松处理 Bitmap (BMP) 和 Device Independent Bitmap (DIB) 文件，从而高效地操作和处理光栅图像。通过对图像执行各种操作，此 API 简化了工作流程，为开发人员提供了在其软件应用中使用 BMP 和 DIB 格式的可靠工具包。

```csharp
public sealed class BmpImage : RasterCachedImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BmpImage](bmpimage/#constructor)(RasterImage) | 通过使用 RasterImage 对象初始化，轻松创建 `BmpImage` 类的新实例。非常适合希望无缝将现有光栅图像转换为 BmpImage 格式的开发人员，确保兼容性并便于集成到其项目中。 |
| [BmpImage](bmpimage/#constructor_5)(Stream) | 通过使用此构造函数并以流作为输入，轻松开始使用 `BmpImage` 类并初始化新实例。非常适合希望从各种数据源方便地使用 BmpImage 对象的开发人员，确保灵活性和易于集成。 |
| [BmpImage](bmpimage/#constructor_7)(string) | 使用此构造函数轻松开始使用 BmpImage 类并初始化新实例。非常适合希望快速高效使用 `BmpImage` 对象的开发人员。 |
| [BmpImage](bmpimage/#constructor_2)(int, int) | 通过使用指定的宽度和高度参数创建新实例，轻松开始使用 `BmpImage` 类。非常适合希望以自定义尺寸生成 BmpImage 对象的开发人员，确保灵活性并便于集成到其项目中。 |
| [BmpImage](bmpimage/#constructor_3)(int, int, ushort, IColorPalette) | 通过使用宽度、高度、位深度和调色板等参数初始化新实例，顺畅地开始使用 `BmpImage` 类。非常适合希望以简便方式创建具有自定义尺寸和颜色配置的 BmpImage 对象的开发人员，确保项目的灵活性和高效性。 |
| [BmpImage](bmpimage/#constructor_1)(RasterImage, ushort, BitmapCompression, double, double) | 通过使用 rasterImage 并指定 bitsPerPixel 和 compression 等参数创建新实例，顺畅地开始使用 `BmpImage` 类。非常适合希望以简便方式处理 BmpImage 对象的开发人员，确保项目的灵活性和高效性。 |
| [BmpImage](bmpimage/#constructor_6)(Stream, ushort, BitmapCompression, double, double) | 通过使用流并指定 bitsPerPixel 和 compression 等参数创建新实例，顺畅地开始使用 `BmpImage` 类。非常适合希望以简便方式处理 BmpImage 对象的开发人员，确保项目的灵活性和高效性。 |
| [BmpImage](bmpimage/#constructor_8)(string, ushort, BitmapCompression, double, double) | 使用此构造函数并指定路径、bitsPerPixel 和 compression 等参数，轻松创建 `BmpImage` 类的新实例。非常适合希望快速高效初始化 BmpImage 对象并精确控制图像特性的开发人员。 |
| [BmpImage](bmpimage/#constructor_4)(int, int, ushort, IColorPalette, BitmapCompression, double, double) | 使用此构造函数并指定宽度、高度、bitsPerPixel 和调色板等参数，轻松创建 `BmpImage` 类的新实例。非常适合希望以便捷方式生成具有自定义尺寸和颜色配置的 BmpImage 对象的开发人员，确保项目的灵活性和易于集成。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| [BitmapInfoHeader](../../aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/) { get; } | 使用此简洁函数快速获取位图图像的关键细节。非常适合需要检索图像头信息的开发人员。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bmpimage/bitsperpixel/) { get; } | 使用此属性轻松获取图像的每像素位数。非常适合希望快速了解图像质量和深度的开发人员。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Compression](../../aspose.imaging.fileformats.bmp/bmpimage/compression/) { get; } | 使用此属性轻松获取图像使用的压缩类型。非常适合需要快速获取图像压缩信息的开发人员。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.bmp/bmpimage/fileformat/) { get; } | 使用此友好属性轻松获取文件格式值。非常适合希望快速获取文件格式信息的开发人员。 |
| override [HasAlpha](../../aspose.imaging.fileformats.bmp/bmpimage/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | 获取或设置一个值，指示此 [`RasterImage`](../../aspose.imaging/rasterimage/) 实例是否具有透明颜色。 |
| override [Height](../../aspose.imaging.fileformats.bmp/bmpimage/height/) { get; } | 使用此属性轻松获取图像的高度。非常适合需要快速获取图像尺寸信息的开发人员。 |
| override [HorizontalResolution](../../aspose.imaging.fileformats.bmp/bmpimage/horizontalresolution/) { get; set; } | 此属性允许您轻松获取或设置 [`RasterImage`](../../aspose.imaging/rasterimage/) 对象的水平分辨率（以每英寸像素数衡量）。非常适合需要对应用程序中的图像分辨率进行精确控制的开发人员。 |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| override [RawDataFormat](../../aspose.imaging.fileformats.bmp/bmpimage/rawdataformat/) { get; } | 使用此友好函数轻松获取原始数据的格式。非常适合希望快速获取数据格式关键信息的开发人员。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| override [RawLineSize](../../aspose.imaging.fileformats.bmp/bmpimage/rawlinesize/) { get; } | 使用此简洁属性快速获取每行原始数据的字节大小。非常适合需要高效处理原始图像数据的开发人员。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | 获取图像透明颜色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| override [VerticalResolution](../../aspose.imaging.fileformats.bmp/bmpimage/verticalresolution/) { get; set; } | 使用此属性轻松获取或设置此 [`RasterImage`](../../aspose.imaging/rasterimage/) 对象的垂直分辨率（以每英寸像素数衡量）。非常适合在其应用程序中需要对图像分辨率进行精确控制的开发人员。 |
| override [Width](../../aspose.imaging.fileformats.bmp/bmpimage/width/) { get; } | 使用此属性轻松获取图像的宽度。非常适合希望快速获取图像尺寸信息的开发人员。 |
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
| override [GetDefaultOptions](../../aspose.imaging.fileformats.bmp/bmpimage/getdefaultoptions/)(object[]) | 使用此简洁方法轻松检索默认选项。适用于希望快速访问默认图像设置或配置的开发者。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
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
| override [SetResolution](../../aspose.imaging.fileformats.bmp/bmpimage/setresolution/)(double, double) | 使用此用户友好方法轻松调整您的[`RasterImage`](../../aspose.imaging/rasterimage/)分辨率。完美适用于希望在应用程序中精确控制图像分辨率的开发者。 |
| override [ToBitmap](../../aspose.imaging.fileformats.bmp/bmpimage/tobitmap/)() | 使用此简易方法轻松将光栅图像转换为位图。对于需要在不同图像格式之间无缝切换的开发者而言，这非常理想。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

解压缩先前使用 DXT1 压缩算法压缩的 BMP 图像。

```csharp
[C#]

using (var image = Image.Load("CompressedTiger.bmp"))
{
    image.Save("DecompressedTiger.bmp", new BmpOptions());
}
```

使用 DXT1 压缩算法压缩 BMP 图像。

```csharp
[C#]

using (var image = Image.Load("Tiger.bmp"))
{
    image.Save("CompressedTiger.bmp", new BmpOptions { Compression = BitmapCompression.Dxt1 });
}
```

示例展示了如何使用带 Telea 算法的 Graphics Path 从图像中移除任意对象。

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new TeleaWatermarkOptions(mask);

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

示例展示了如何使用 Rgb 压缩类型导出 BmpImage。

```csharp
[C#]

string sourcePath = "input.png";
// 从文件加载 PNG 图像。
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP 图像默认以透明度支持保存，这是通过使用 BitmapCompression.Bitfields 压缩方法实现的。
    // 要使用 Rgb 压缩方法保存 BMP 图像，应指定 Compression 属性设置为 BitmapCompression.Rgb 的 BmpOptions。
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

示例展示了如何使用带 Content Aware fill 算法的 Graphics Path 从图像中移除任意对象。

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new ContentAwareFillWatermarkOptions(mask) 
    { 
        MaxPaintingAttempts = 4
    };

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

以下示例展示了如何创建指定尺寸的 BMP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 使用简单的线性红黑渐变填充图像。
    int width = bmpImage.Width;
    int height = bmpImage.Height;
    for (int y = 0; y < height; y++)
    {
        for (int x = 0; x < width; x++)
        {
            int hue = (255 * x) / width;
            bmpImage.SetPixel(x, y, Aspose.Imaging.Color.FromArgb(255, hue, 0, 0));
        }
    }

    using (System.IO.FileStream stream = new System.IO.FileStream(dir + "output.bmp", System.IO.FileMode.Create))
    {
        bmpImage.Save(stream);
    }
}
```

示例展示了如何从 Png 文件导出 BmpImage 并保留 alpha 通道，以透明度保存 Bmp 文件。

```csharp
[C#]

string sourcePath = "input.png";
// 从文件加载 PNG 图像。
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP 图像默认以透明度支持保存。
    // 如果您想显式指定此模式，应将 BmpOptions 的 Compression 属性设置为 BitmapCompression.Bitfields。
    // BitmapCompression.Bitfields 压缩方法是 BmpOptions 中的默认压缩方法。
    // 因此，通过以下任一方式都可以实现导出带透明度的 Bmp 图像的相同结果。
    // 使用隐式默认选项：
    pngImage.Save(outputPath);
    // 使用显式默认选项：
    pngImage.Save(outputPath, new BmpOptions());
    // 指定 BitmapCompression.Bitfields 压缩方法：
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

### 另请参见

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


