---
title: PngImage
second_title: Aspose.Imaging for .NET API 参考
description: 新的 png 图像
type: docs
weight: 7450
url: /zh/aspose.imaging.fileformats.png/pngimage/
---
## PngImage class

新的 png 图像。

```csharp
public class PngImage : RasterCachedImage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PngImage](pngimage#constructor_1)(RasterImage) | 初始化[`PngImage`](../pngimage)类. |
| [PngImage](pngimage#constructor_5)(Stream) | 初始化[`PngImage`](../pngimage)类. |
| [PngImage](pngimage#constructor_6)(string) | 初始化[`PngImage`](../pngimage)类. |
| [PngImage](pngimage#constructor_3)(int, int) | 初始化[`PngImage`](../pngimage)类. |
| [PngImage](pngimage#constructor_2)(RasterImage, PngColorType) | 初始化[`PngImage`](../pngimage)类. |
| [PngImage](pngimage#constructor_7)(string, PngColorType) | 初始化[`PngImage`](../pngimage)类. |
| [PngImage](pngimage#constructor_4)(int, int, PngColorType) | 初始化[`PngImage`](../pngimage)类. |
| [PngImage](pngimage#constructor)(PngOptions, int, int) | 初始化[`PngImage`](../pngimage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| override [BackgroundColor](../../aspose.imaging.fileformats.png/pngimage/backgroundcolor) { get; set; } | 获取背景颜色。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.png/pngimage/bitsperpixel) { get; } | 获取每个像素的位数。 |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container) { get; } | 获取[`Image`](../../aspose.imaging/image)容器. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| override [FileFormat](../../aspose.imaging.fileformats.png/pngimage/fileformat) { get; } | 获取文件格式的值 |
| override [HasAlpha](../../aspose.imaging.fileformats.png/pngimage/hasalpha) { get; } | 获取一个值，表示这个实例是否有alpha。 |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor) { get; set; } | 获取一个值，表示是否有背景色。 |
| override [HasTransparentColor](../../aspose.imaging.fileformats.png/pngimage/hastransparentcolor) { get; set; } | 获取一个表示图像是否具有透明色的值。 |
| override [Height](../../aspose.imaging.fileformats.png/pngimage/height) { get; } | 获取高度。 |
| override [HorizontalResolution](../../aspose.imaging.fileformats.png/pngimage/horizontalresolution) { get; set; } | 获取或设置水平分辨率。 |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | 获取此图像的不透明度。 |
| [Interlaced](../../aspose.imaging.fileformats.png/pngimage/interlaced) { get; } | 获取一个值，该值指示这是否[`PngImage`](../pngimage)是隔行扫描的。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | 获取当前是否缓存图像数据的值。 |
| [IsInterlaced](../../aspose.imaging.fileformats.png/pngimage/isinterlaced) { get; } | 获取一个值，指示此图像实例是否是隔行扫描的。 |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | 获取一个值，指示是否可以加载原始数据。 |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | 获取或设置一个值，该值指示是否必须对图像分量进行预乘。 |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | 获取或设置自定义颜色转换器 |
| override [RawDataFormat](../../aspose.imaging.fileformats.png/pngimage/rawdataformat) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | 获取当前的原始数据设置。请注意，使用这些设置时，数据加载时无需转换。 |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | 以字节为单位获取原始行大小。 |
| [Size](../../aspose.imaging/image/size) { get; } | 获取图像大小。 |
| override [TransparentColor](../../aspose.imaging.fileformats.png/pngimage/transparentcolor) { get; set; } | 获取透明色。 |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | 获取或设置是否更新 XMP 元数据的值。 |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | 获取指示是否使用图像调色板的值。 |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | 获取或设置一个值，指示当原始数据加载可用时是否使用原始数据加载。 |
| override [VerticalResolution](../../aspose.imaging.fileformats.png/pngimage/verticalresolution) { get; set; } | 获取或设置垂直分辨率。 |
| override [Width](../../aspose.imaging.fileformats.png/pngimage/width) { get; } | 获取宽度。 |
| override [XmpData](../../aspose.imaging.fileformats.png/pngimage/xmpdata) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | 图像对比 |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | 图像的 Gamma 校正。 |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | 图像的 Gamma 校正。 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | 具有预定义阈值的图像二值化 |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | 使用 Otsu 阈值对图像进行二值化 |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | 判断图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| override [Crop](../../aspose.imaging/rastercachedimage/crop)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.imaging/rasterimage/crop)(int, int, int, int) | 使用班次裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | 对当前图像执行抖动。 |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动。 |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | 过滤指定的矩形。 |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | 获取图像 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.png/pngimage/getdefaultoptions)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | 获取默认的原始数据数组。 |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| override [GetModifyDate](../../aspose.imaging.fileformats.png/pngimage/getmodifydate)(bool) | 获取上次修改资源图像的日期和时间。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.png/pngimage/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存它[`Save`](../../aspose.imaging/datastreamsupporter/save)方法，将产生每像素8位的输出PNG图像。 为了避免它并以每像素1位保存PNG图像，使用此方法获取相应的保存选项并将它们 传递给[`Save`](../../aspose.imaging/image/save)方法作为第二个参数。 |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | 获取图像像素。 |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | 获取倾斜角度。 该方法适用于扫描的文本文档，确定扫描时的倾斜角度。 |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | 将图像转换为其灰度表示 |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | 以 CMYK 格式加载像素。 |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 部分按包加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | 部分按包加载像素。 |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | 角度归一化。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle)和[`Rotate`](../../aspose.imaging/rasterimage/rotate)方法. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | 角度归一化。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle)和[`Rotate`](../../aspose.imaging/rasterimage/rotate)方法. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 alpha 值以保存平滑边缘。 |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 alpha 值以保存平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | 将所有不透明的颜色替换为新颜色并保留原始 alpha 值以保存平滑的边缘。 注意：如果在不透明的图像上使用它，所有颜色都将替换为一个颜色。 |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | 将所有不透明的颜色替换为新颜色并保留原始 alpha 值以保存平滑的边缘。 注意：如果在不透明的图像上使用它，所有颜色都将替换为一个颜色。 |
| [Resize](../../aspose.imaging/image/resize)(int, int) | 调整图像大小。默认NearestNeighbourResample已使用。 |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | 按比例调整高度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | 按比例调整宽度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip)(RotateFlipType) | 旋转、翻转或旋转和翻转图像。 |
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

此示例显示如何从文件加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件中加载 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // 将图像转换为灰度表示
    pngImage.Grayscale();

    // 保存到文件。
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### 也可以看看

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
