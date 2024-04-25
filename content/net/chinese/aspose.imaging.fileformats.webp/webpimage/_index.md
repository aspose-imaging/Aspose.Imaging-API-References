---
title: WebPImage
second_title: Aspose.Imaging for .NET API 参考
description: 一个webp图像
type: docs
weight: 8080
url: /zh/aspose.imaging.fileformats.webp/webpimage/
---
## WebPImage class

一个webp图像。

```csharp
public sealed class WebPImage : RasterCachedMultipageImage, IMultipageImageExt
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [WebPImage](webpimage#constructor)(RasterImage) | 初始化[`WebPImage`](../webpimage)rasterImage. 中的类 |
| [WebPImage](webpimage#constructor_4)(Stream) | 初始化[`WebPImage`](../webpimage) class 来自流. |
| [WebPImage](webpimage#constructor_6)(string) | 初始化[`WebPImage`](../webpimage)文件中的类. |
| [WebPImage](webpimage#constructor_1)(RasterImage, LoadOptions) | 初始化[`WebPImage`](../webpimage)rasterImage. 中的类 |
| [WebPImage](webpimage#constructor_5)(Stream, LoadOptions) | 初始化[`WebPImage`](../webpimage)流中的类. |
| [WebPImage](webpimage#constructor_7)(string, LoadOptions) | 初始化[`WebPImage`](../webpimage)文件中的类. |
| [WebPImage](webpimage#constructor_2)(int, int, WebPOptions) | 初始化[`WebPImage`](../webpimage)具有空图像的类。 |
| [WebPImage](webpimage#constructor_3)(int, int, WebPOptions, LoadOptions) | 初始化[`WebPImage`](../webpimage)具有空图像的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | 获取每像素计数的图像位数。 |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container) { get; } | 获取[`Image`](../../aspose.imaging/image)容器. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| override [FileFormat](../../aspose.imaging.fileformats.webp/webpimage/fileformat) { get; } | 获取文件格式的值 |
| override [HasAlpha](../../aspose.imaging.fileformats.webp/webpimage/hasalpha) { get; } | 获取有 alpha 通道。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | 获取或设置图像是否有背景色的值。 |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | 获取一个表示图像是否具有透明色的值。 |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | 获取或设置此图像的水平分辨率，以每英寸像素为单位[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | 获取当前是否缓存图像数据的值。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | 获取一个值，指示是否可以加载原始数据。 |
| [Options](../../aspose.imaging.fileformats.webp/webpimage/options) { get; } | 获取或设置选项。 |
| override [PageCount](../../aspose.imaging.fileformats.webp/webpimage/pagecount) { get; } | 获取页数。 |
| override [PageExportingAction](../../aspose.imaging.fileformats.webp/webpimage/pageexportingaction) { get; set; } | 获取或设置页面导出动作。 请注意，设置此方法执行后会自动释放页面资源。 会在每页保存前执行。 |
| override [Pages](../../aspose.imaging.fileformats.webp/webpimage/pages) { get; } | 获取块。 |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | 获取或设置一个值，该值指示是否必须对图像分量进行预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | 获取当前的原始数据设置。请注意，使用这些设置时，数据加载时无需转换。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | 以字节为单位获取原始行大小。 |
| [Size](../../aspose.imaging/image/size) { get; } | 获取图像大小。 |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | 获取图像透明色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | 获取或设置是否更新 XMP 元数据的值。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | 获取指示是否使用图像调色板的值。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | 获取或设置一个值，指示当原始数据加载可用时是否使用原始数据加载。 |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | 获取或设置此对象的垂直分辨率，以每英寸像素为单位[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | 获取图像宽度。 |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | 从帧中获取或设置 XMP 数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.webp/webpimage/addblock)(IFrame) | 添加一个新的 Webp 块。 |
| [AddPage](../../aspose.imaging.fileformats.webp/webpimage/addpage)(RasterImage) | 将页面添加到图像。 |
| override [AdjustBrightness](../../aspose.imaging.fileformats.webp/webpimage/adjustbrightness)(int) | 调整一个*brightness*对于图像. |
| override [AdjustContrast](../../aspose.imaging.fileformats.webp/webpimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image)对比 |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma#adjustgamma)(float) | 图像的 Gamma 校正。 |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma#adjustgamma_1)(float, float, float) | 图像的 Gamma 校正。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeBradley](../../aspose.imaging.fileformats.webp/webpimage/binarizebradley#binarizebradley_1)(double, int) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeFixed](../../aspose.imaging.fileformats.webp/webpimage/binarizefixed)(byte) | 具有预定义阈值的图像二值化 |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.webp/webpimage/binarizeotsu)() | 使用 Otsu 阈值对图像进行二值化 |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | 缓存私有数据。 |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | 判断图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| [ClearBlocks](../../aspose.imaging.fileformats.webp/webpimage/clearblocks)() | 清除所有 Webp 块。 |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop#crop)(Rectangle) | 裁剪图像。 |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop#crop_1)(int, int, int, int) | 使用班次裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | 对当前图像执行抖动。 |
| override [Dither](../../aspose.imaging.fileformats.webp/webpimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动。 |
| override [Filter](../../aspose.imaging.fileformats.webp/webpimage/filter)(Rectangle, FilterOptionsBase) | 过滤指定的矩形。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | 获取图像 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | 获取默认的原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | 获取上次修改资源图像的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存它[`Save`](../../aspose.imaging/datastreamsupporter/save)方法，将产生每像素8位的输出PNG图像。 为了避免它并以每像素1位保存PNG图像，使用此方法获取相应的保存选项并将它们 传递给[`Save`](../../aspose.imaging/image/save)方法作为第二个参数。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | 获取图像像素。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | 获取倾斜角度。 该方法适用于扫描的文本文档，确定扫描时的倾斜角度。 |
| override [Grayscale](../../aspose.imaging.fileformats.webp/webpimage/grayscale)() | 将图像转换为其灰度表示 |
| [InsertBlock](../../aspose.imaging.fileformats.webp/webpimage/insertblock)(int, IFrame) | 添加一个新的 Webp 块。 |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | 以 CMYK 格式加载像素。 |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 部分按包加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | 部分按包加载像素。 |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | 角度归一化。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle)和[`Rotate`](../../aspose.imaging/rasterimage/rotate)方法. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | 角度归一化。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用!:GetSkewAngle和[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate)方法. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [RemoveBlock](../../aspose.imaging.fileformats.webp/webpimage/removeblock)(IFrame) | 移除 Webp 块。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 alpha 值以保存平滑边缘。 |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 alpha 值以保存平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | 将所有不透明的颜色替换为新颜色并保留原始 alpha 值以保存平滑的边缘。 注意：如果在不透明的图像上使用它，所有颜色都将替换为一个颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | 将所有不透明的颜色替换为新颜色并保留原始 alpha 值以保存平滑的边缘。 注意：如果在不透明的图像上使用它，所有颜色都将替换为一个颜色。 |
| [Resize](../../aspose.imaging/image/resize)(int, int) | 调整图像大小。默认NearestNeighbourResample已使用。 |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | 按比例调整高度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | 按比例调整宽度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging.fileformats.webp/webpimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate中心周围的图像。 |
| override [RotateFlip](../../aspose.imaging.fileformats.webp/webpimage/rotateflip)(RotateFlipType) | 仅旋转、翻转或旋转和翻转活动帧。 |
| [Save](../../aspose.imaging/image/save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流中。 |
| override [Save](../../aspose.imaging/image/save)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | 为指定位置设置图像 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | 为此设置分辨率[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | 将光栅图像转换为位图。 |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | 将整个扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | 将整个扫描线写入指定的扫描线索引。 |

### 例子

此示例说明如何从文件加载 WebP 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件中加载 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // 保存为 PNG
    // 请注意，只有活动帧将存储到 PNG，因为 PNG 不是多页格式。
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../aspose.imaging.fileformats.webp)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
