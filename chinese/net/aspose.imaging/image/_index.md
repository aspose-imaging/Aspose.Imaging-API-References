---
title: "Image 类"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Image 类。该图像是所有图像类型的基类"
type: docs
weight: 9860
url: /zh/net/aspose.imaging/image/
---
## Image class

Image 是所有类型图像的基类。

```csharp
public abstract class Image : DataStreamSupporter, IMetadataContainer, IObjectWithBounds
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel/) { get; } | 获取图像的每像素位数。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 `Image` 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| virtual [FileFormat](../../aspose.imaging/image/fileformat/) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| abstract [Height](../../aspose.imaging/image/height/) { get; } | 获取图像高度。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| abstract [Width](../../aspose.imaging/image/width/) { get; } | 获取图像宽度。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.imaging/image/create/#create_3)(Image[]) | 使用指定的图像作为页面创建新图像 |
| static [Create](../../aspose.imaging/image/create/#create)(MultipageCreateOptions) | 创建指定的多页创建选项。 |
| static [Create](../../aspose.imaging/image/create/#create_5)(string[]) | 创建包含指定文件的多页图像。 |
| static [Create](../../aspose.imaging/image/create/#create_4)(Image[], bool) | 使用指定的图像作为页面创建新图像。 |
| static [Create](../../aspose.imaging/image/create/#create_6)(string[], bool) | 创建包含指定文件的多页图像。 |
| static [Create](../../aspose.imaging/image/create/#create_1)(ImageOptionsBase, int, int) | 使用指定的创建选项创建新图像。 |
| static [Create](../../aspose.imaging/image/create/#create_2)(ImageOptionsBase, int, int, int[]) | 从提供的像素数组创建一个 [`RasterImage`](../rasterimage/) 实例。验证指定的宽度和高度是否匹配像素数据的尺寸。此方法只能在库处于授权模式时使用。 |
| static [Load](../../aspose.imaging/image/load/#load)(Stream) | 从指定的流加载新图像。 |
| static [Load](../../aspose.imaging/image/load/#load_2)(string) | 从指定的文件路径或 URL 加载新图像。如果 *filePath* 是文件路径，方法仅打开该文件。如果 *filePath* 是 URL，方法会下载文件，将其存储为临时文件，然后打开它。 |
| static [Load](../../aspose.imaging/image/load/#load_1)(Stream, LoadOptions) | 从指定的流加载新图像。 |
| static [Load](../../aspose.imaging/image/load/#load_3)(string, LoadOptions) | 从指定的文件路径或 URL 加载新图像。如果 *filePath* 是文件路径，方法仅打开该文件。如果 *filePath* 是 URL，方法会下载文件，将其存储为临时文件，然后打开它。 |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) 再进行额外的数据加载。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| virtual [Crop](../../aspose.imaging/image/crop/#crop)(Rectangle) | 裁剪指定的矩形。 |
| virtual [Crop](../../aspose.imaging/image/crop/#crop_1)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | 获取基于原始文件设置的选项。这对于保持原始图像的位深度和其他参数不变很有帮助。例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../datastreamsupporter/save/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。为了避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](./save/) 方法。 |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | 移除元数据。 |
| [Resize](../../aspose.imaging/image/resize/#resize)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| abstract [Resize](../../aspose.imaging/image/resize/#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| virtual [Resize](../../aspose.imaging/image/resize/#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/#resizeheightproportionally)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/#resizewidthproportionally)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.imaging/image/rotate/)(float) | 围绕中心旋转图像。 |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip/)(RotateFlipType) | 旋转、翻转或同时旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save/#save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save/#save_4)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save/#save_2)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/#save_5)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| abstract [SetPalette](../../aspose.imaging/image/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，如果此 `Image` 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| static [CanLoad](../../aspose.imaging/image/canload/#canload)(Stream) | 确定是否可以从指定的流加载图像。 |
| static [CanLoad](../../aspose.imaging/image/canload/#canload_2)(string) | 确定是否可以从指定的文件路径加载图像。 |
| static [CanLoad](../../aspose.imaging/image/canload/#canload_1)(Stream, LoadOptions) | 确定是否可以从指定的流加载图像，并可选地使用指定的 *loadOptions*。 |
| static [CanLoad](../../aspose.imaging/image/canload/#canload_3)(string, LoadOptions) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。 |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat/#getfileformat)(Stream) | 获取文件格式。 |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat/#getfileformat_1)(string) | 获取文件格式。 |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | 获取适合当前图像的矩形。 |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | 获取适合当前图像的矩形。 |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight/)(int, int, int) | 获取等比例高度。 |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth/)(int, int, int) | 获取等比例宽度。 |

## 示例

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

使用特定的缩放类型调整图像大小。

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

此示例在磁盘的某个位置创建一个新 Image 文件，位置由 BmpOptions 实例的 Source 属性指定。在创建实际图像之前，设置了 BmpOptions 实例的多个属性。尤其是此情况下指向实际磁盘位置的 Source 属性。

```csharp
[C#]

//创建 BmpOptions 的实例并设置其各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//通过调用 Create 方法创建 Image 实例并使用 BmpOptions 实例进行初始化。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //进行一些图像处理

    // 保存所有更改
    image.Save();
}
```

### 另请参见

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* interface [IMetadataContainer](../imetadatacontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


