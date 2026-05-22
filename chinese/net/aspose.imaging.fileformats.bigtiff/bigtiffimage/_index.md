---
title: "类 BigTiffImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.BigTiff.BigTiffImage 类。使用 BigTiffImage 类，您可以轻松操作 BigTiff 图像格式文件。我们的 API 提供无缝处理和自定义选项，确保对大规模图像数据的最佳处理，具备针对您特定需求量身定制的多功能特性。"
type: docs
weight: 1370
url: /zh/net/aspose.imaging.fileformats.bigtiff/bigtiffimage/
---
## BigTiffImage class

使用 `BigTiffImage` 类，您可以轻松操作 BigTiff 图像格式文件。我们的 API 提供无缝处理和自定义选项，确保对大规模图像数据的最佳处理，具备针对您特定需求量身定制的多功能特性。

```csharp
public sealed class BigTiffImage : TiffImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BigTiffImage](bigtiffimage/#constructor)(TiffFrame) | 通过使用 TiffFrame 参数初始化 `BigTiffImage` 类，创建一个新实例。对于希望以便捷方式使用 BigTiffImage 对象的开发者而言，这非常理想，确保灵活性并易于集成到其项目中。 |
| [BigTiffImage](bigtiffimage/#constructor_1)(TiffFrame[]) | 通过使用 TiffFrames 列表参数初始化 `BigTiffImage` 类的新实例，轻松开始使用该类。对于希望以简洁方式处理包含多个帧的 BigTiffImage 对象的开发者而言，这非常完美，确保项目的高效性。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/activeframe/) { get; set; } | 无缝管理活动帧，促进在指定上下文中的动态导航和操作。让您的应用程序能够高效地与多媒体内容交互，提升用户参与度和生产力。 |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | 获取图像的每像素位数。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ByteOrder](../../aspose.imaging.fileformats.tiff/tiffimage/byteorder/) { get; set; } | 无缝切换 TIFF 文件的字节顺序，确保对数据解释的精确控制。为您的应用程序提供灵活性，以适应多样的文件规范，提升兼容性和数据处理效率。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.bigtiff/bigtiffimage/fileformat/) { get; } | 获取此 [`Image`](../../aspose.imaging/image/) 实例的文件格式。 |
| [Frames](../../aspose.imaging.fileformats.tiff/tiffimage/frames/) { get; } | 检索一个包含 [`TiffFrame`](../../aspose.imaging.fileformats.tiff/tiffframe/) 实例的数组，以实现对 TIFF 图像中各帧的全面访问和操作。利用此数组的力量简化图像处理工作流，确保对视觉内容的精确控制和优化。 |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffimage/hasalpha/) { get; } | 确定图像是否具有 alpha 通道，为渲染和合成操作提供关键信息。集成此功能以优化视觉处理工作流，确保对透明元素的准确表示和操作。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | 获取指示图像是否具有透明颜色的值。 |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | 获取图像高度。 |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution/) { get; set; } | 获取指定 [`Image`](../../aspose.imaging/image/) 的水平分辨率（每英寸像素数），便于精确的调整和渲染能力。轻松访问关键图像元数据，提升图像处理工作流的流畅性，增强用户体验。 |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | 获取指示图像数据当前是否已缓存的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | 获取指示是否可进行原始数据加载的值。 |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | 获取或设置帧的 XMP 数据。 |
| override [PageCount](../../aspose.imaging.fileformats.tiff/tiffimage/pagecount/) { get; } | 检索指定文档的总页数，以便高效导航和管理多页内容。将此功能整合到用户体验中，实现对完整文档结构的无缝访问。 |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.tiff/tiffimage/pages/) { get; } | 无缝访问文档的页面，实现内容结构内的动态导航和操作。为您的应用提供高效的单页访问，促进文档处理的流畅性并提升用户交互体验。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| override [PremultiplyComponents](../../aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/) { get; set; } | 指示组件是否需要预乘，以确保对视觉元素的高效处理。通过切换此属性来提升渲染过程，简化图形工作流，实现性能优化。 |
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
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/verticalresolution/) { get; set; } | 获取指定 [`Image`](../../aspose.imaging/image/) 的垂直分辨率（每英寸像素数），实现精确的调整和渲染优化。轻松利用关键图像数据，简化图像处理工作流，确保应用程序的卓越质量和性能。 |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | 获取图像宽度。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.imaging.fileformats.tiff/tiffimage/add/)(TiffImage) | 将指定图像的帧无缝添加到当前帧中，整合其内容并提升组合灵活性。集成此方法以简化应用中的帧管理和操作，促进对多帧图像的高效处理。 |
| [AddFrame](../../aspose.imaging.fileformats.tiff/tiffimage/addframe/)(TiffFrame) | 将指定帧无缝合并到图像中，扩展其内容和多样性。使用此方法提升图像的组合与管理，使应用能够高效处理多帧图像。 |
| [AddFrames](../../aspose.imaging.fileformats.tiff/tiffimage/addframes/)(TiffFrame[]) | 将帧数组无缝集成到图像中，丰富其内容和多样性。利用此方法提升图像的组合与管理，实现对多帧图像的高效处理。 |
| override [AddPage](../../aspose.imaging.fileformats.bigtiff/bigtiffimage/addpage/)(RasterImage) | 使用此直观方法轻松为 BigTiff 图像添加新页面，轻松扩展图像。非常适合希望动态增强多页图像内容的开发者。 |
| override [AdjustBrightness](../../aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness/)(int) | 实现对图像的 *brightness* 调整，允许修改整体亮度水平。将此方法纳入图像处理工作流，以提升可见性并改善应用程序中图像的视觉质量。 |
| override [AdjustContrast](../../aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast/)(float) | 提升 [`Image`](../../aspose.imaging/image/) 实例的对比度，放大其明暗区域的差异。集成此功能可改善图像的视觉清晰度和整体质量。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/)(float) | 对图像进行伽马校正，调整像素强度以实现期望的色彩平衡。将此方法纳入图像处理工作流，以提升视觉质量并提高后续分析或显示任务的准确性。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/)(float, float, float) | 使用红、绿、蓝通道的独立系数对图像进行伽马校正，实现对色彩平衡和对比度的细致调节。将此方法集成到图像处理管线中，以实现对颜色渲染的精确控制并提升视觉保真度。 |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffimage/alignresolutions/)() | 实现 AlignResolutions 辅助方法以同步水平和垂直分辨率，确保图像尺寸的一致性。此功能通过统一分辨率参数，简化图像处理工作流，优化跨平台和设备的视觉质量与一致性。 |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | 计算提取数据与原始密码之间的相似度百分比。 |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | 自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.imaging.fileformats.tiff/tiffimage/binarizebradley/)(double, int) | 在图像上实现二值化，采用 Bradley 自适应阈值算法结合积分图阈值。该方法根据图像邻域动态计算局部阈值，提升对不同光照条件的适应性，并确保后续处理任务的稳健分割。 |
| override [BinarizeFixed](../../aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/)(byte) | 使用预定义阈值对图像进行二值化，将其转换为前景与背景区域明确的二值图像。将此方法纳入图像处理工作流，以促进分割和特征提取任务，提高图像分析的准确性和效率。 |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/)() | 利用 Otsu 阈值法对图像进行二值化，自动依据图像直方图确定最佳阈值。将此方法集成到图像处理工作流中，实现有效的分割和特征提取，提升图像分析任务的准确性和可靠性。 |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | 将此图像实例与 *overlay* 图像混合。 |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | 缓存数据为私有。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop/)(Rectangle) | 使用指定的矩形区域裁剪图像，实现对所需内容的精确选择。将此方法纳入图像处理工作流，以高效去除不需要的区域，聚焦关键细节，提升图像的整体清晰度和构图。 |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop/)(int, int, int, int) | 通过指定左、右、上、下方向的偏移量对图像进行裁剪。此方法实现对图像所需部分的精确选取，便于高效去除不需要的区域并聚焦关键内容。将此功能集成到图像处理管线中，根据需要提升图像的清晰度和构图。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.imaging.fileformats.tiff/tiffimage/dither/)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动处理，以提升视觉质量并减少颜色条带伪影。将此方法纳入图像处理工作流，确保颜色过渡更平滑，提升整体图像外观和清晰度。 |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| override [Filter](../../aspose.imaging.fileformats.tiff/tiffimage/filter/)(Rectangle, FilterOptionsBase) | 在指定的矩形内过滤内容，应用指定的图像处理滤镜以增强或修改所选区域。将此方法集成到图像操作工作流，以在应用程序中实现针对性的增强或转换。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | 获取资源图像最近修改的日期和时间。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions/)() | 检索源文件设置派生的选项，便于无缝保留关键参数，如位深度及原始图像的其他重要属性。使用此方法保持图像处理任务的保真度和一致性，确保在不进行不必要修改的情况下获得最佳结果。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，它将生成每像素 8 位的 PNG 图像。若要避免此情况并以 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。 |
| override [Grayscale](../../aspose.imaging.fileformats.tiff/tiffimage/grayscale/)() | 将图像转换为灰度表示，转化为单通道图像，每个像素表示强度。将此方法集成到图像处理管线中，以简化分析并提升对基于灰度算法的兼容性，促进应用中各种计算机视觉和图像分析任务的实现。 |
| [InsertFrame](../../aspose.imaging.fileformats.tiff/tiffimage/insertframe/)(int, TiffFrame) | 在帧序列的指定索引处插入新帧，确保对帧排列的精确控制。使用此方法有效管理帧序列，促进在应用中对图像内容的动态操作和组织。 |
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
| override [NormalizeAngle](../../aspose.imaging.fileformats.tiff/tiffimage/normalizeangle/)(bool, Color) | 利用专为扫描文本文件设计的 NormalizeAngle 方法来校正倾斜的扫描，确保准确对齐。将此功能无缝集成到您的文本处理工作流中，以提升文档可读性和质量，提高文本识别和分析任务的整体效率。此方法使用 [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.imaging.fileformats.tiff/tiffimage/rotate/) 方法。 |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedmultipageimage/normalizehistogram/)() | 归一化图像直方图——调整像素值以使用全部可用范围。 |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe/)(int) | 轻松地根据索引删除图像序列中的帧，简化应用程序中的帧管理。集成此功能可提升帧操作的效率和精度，促进图像内容的无缝组织和呈现。 |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe/)(TiffFrame) | 高效地从图像序列中移除指定帧，帮助简化应用程序中的帧管理。集成此功能可提升帧操作的精度和灵活性，确保图像内容的无缝组织和呈现。 |
| override [RemoveMetadata](../../aspose.imaging.fileformats.tiff/tiffimage/removemetadata/)() | 通过将此 [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) 和 [`ExifData`](../../aspose.imaging.exif/ihasexifdata/exifdata/) 的值设为 `null` 来移除该图像实例的元数据。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | 将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceFrame](../../aspose.imaging.fileformats.tiff/tiffimage/replaceframe/)(int, TiffFrame) | 在指定位置无缝替换为另一帧，促进图像序列中的动态帧管理。集成此方法可提升帧操作的灵活性和精度，确保应用程序内图像内容的最佳组织和呈现。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize/)(int, int, ImageResizeSettings) | 根据指定设置调整图像大小，实现对尺寸、宽高比和缩放行为的精确控制。将此方法集成到图像处理工作流中，以实现符合应用程序特定需求的自定义缩放操作。 |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize/)(int, int, ResizeType) | 根据指定的缩放类型调整图像大小，在保持宽高比或使用特定缩放算法的同时，实现图像尺寸的灵活调整。将此方法纳入图像处理工作流，以在应用程序中实现对缩放操作的精确控制。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally/)(int, ResizeType) | 对图像高度进行比例调整，保持宽高比以确保视觉一致性。使用此方法在应用程序中动态调整图像大小，确保在各种平台和设备上实现最佳显示且不影响内容质量。 |
| [ResizeProportional](../../aspose.imaging.fileformats.tiff/tiffimage/resizeproportional/)(int, int, ResizeType) | 对图像进行比例缩放操作，在调整尺寸的同时保持宽高比。使用此方法在应用程序中动态缩放图像，确保内容完整性的视觉表现一致。比例缩放将根据 *newWidth*/width 和 *newHeight*/height 的比例对每个帧进行缩放。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally/)(int, ResizeType) | 在保持宽高比的前提下调整图像宽度，确保比例缩放以获得最佳视觉呈现。利用此方法在应用程序中动态缩放图像，实现跨各种显示环境的一致且美观的渲染。 |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffimage/rotate/)(float, bool, Color) | 围绕中心点按指定角度旋转图像，实现精确的方向调整。将此功能纳入图像处理流水线，以便进行准确的变换，确保应用程序中视觉内容的最佳对齐和呈现。 |
| override [RotateFlip](../../aspose.imaging.fileformats.tiff/tiffimage/rotateflip/)(RotateFlipType) | 仅在活动帧上执行旋转、翻转或两者的组合操作。此方法可对图像序列中的单帧进行精确操作，提升应用程序中图像编辑和合成的灵活性。 |
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
| override [SetResolution](../../aspose.imaging.fileformats.tiff/tiffimage/setresolution/)(double, double) | 为指定的 [`RasterImage`](../../aspose.imaging/rasterimage/) 设置分辨率，实现对图像渲染和显示属性的精确控制。集成此功能可优化视觉输出，并确保与多种输出设备和平台的兼容性，提升整体用户体验。 |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | 将光栅图像转换为位图。此方法在 .Net7.0 及更高版本中不受支持。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

### 另请参见

* class [TiffImage](../../aspose.imaging.fileformats.tiff/tiffimage/)
* namespace [Aspose.Imaging.FileFormats.BigTiff](../../aspose.imaging.fileformats.bigtiff/)
* assembly [Aspose.Imaging](../../)


