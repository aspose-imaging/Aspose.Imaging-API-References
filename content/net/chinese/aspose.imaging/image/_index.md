---
title: Image
second_title: Aspose.Imaging for .NET API 参考
description: 图像是所有类型图像的基类
type: docs
weight: 9660
url: /zh/aspose.imaging/image/
---
## Image class

图像是所有类型图像的基类。

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | 获取每像素计数的图像位数。 |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container) { get; } | 获取[`Image`](../image)容器. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | 获取或设置图像是否有背景色的值。 |
| abstract [Height](../../aspose.imaging/image/height) { get; } | 获取图像高度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | 获取一个值，表示对象的数据当前是否被缓存，不需要读取数据。 |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| [Size](../../aspose.imaging/image/size) { get; } | 获取图像大小。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | 获取指示是否使用图像调色板的值。 |
| abstract [Width](../../aspose.imaging/image/width) { get; } | 获取图像宽度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | 使用指定的图像作为 pages 创建一个新图像 |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | 将指定图像作为页面创建一个新图像。 |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | 使用指定的创建选项创建新图像。 |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | 从指定流加载新图像。 |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | 从指定文件加载新图像。 |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | 从指定流加载新图像。 |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | 从指定文件加载新图像。 |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | 判断图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | 获取默认选项。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存它[`Save`](../datastreamsupporter/save)方法，将产生每像素8位的输出PNG图像。 为了避免它并以每像素1位保存PNG图像，使用此方法获取相应的保存选项并将它们 传递给[`Save`](./save)方法作为第二个参数。 |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | 调整图像大小。默认NearestNeighbourResample已使用。 |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | 按比例调整高度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | 按比例调整宽度。默认NearestNeighbourResample已使用。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | 旋转、翻转或旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save#save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流中。 |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | 设置图像调色板。 |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | 确定是否可以从指定流中加载图像。 |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | 判断是否可以从指定的文件路径加载图片。 |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | 确定是否可以从指定的流加载图像，并且可以选择使用指定的*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | 确定是否可以从指定的文件路径加载图像，并且可以选择使用指定的打开选项。 |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | 获取文件格式。 |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | 获取文件格式。 |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | 获取适合当前图像的矩形。 |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | 获取适合当前图像的矩形。 |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | 获取比例高度。 |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | 获取比例宽度。 |

### 例子

确定图像是否使用调色板。

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

使用特定的调整大小类型调整图像大小。

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

此示例在 BmpOptions 实例的 Source 属性指定的某个磁盘位置创建一个新的图像文件。 BmpOptions 实例的几个属性在创建实际图像之前设置。特别是 Source 属性，在这种情况下指的是实际的磁盘位置。

```csharp
[C#]

//创建一个BmpOptions的实例并设置它的各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建一个 FileCreateSource 的实例并将其分配为 BmpOptions 实例的 Source
//第二个布尔参数确定要创建的文件是否为IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//创建一个Image实例并通过调用Create方法用BmpOptions实例初始化它
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //做一些图像处理

    // 保存所有更改
    image.Save();
}
```

### 也可以看看

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
