---
title: "BmpOptions 类"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.BmpOptions 类。该 API 用于 BMP 和 DIB 栅格图像格式创建选项，为开发者提供了多功能工具集，以生成自定义的 Bitmap BMP 和设备独立位图 DIB 图像。使用此 API，您可以精确定义图像特性，如每像素位数、压缩级别和压缩类型，从而定制输出以满足特定需求。这个功能丰富的 API 使开发者能够轻松灵活地创建高质量的定制栅格图像，适用于各种应用。"
type: docs
weight: 10260
url: /zh/net/aspose.imaging.imageoptions/bmpoptions/
---
## BmpOptions class

BMP 和 DIB 栅格图像格式创建选项的 API 为开发者提供了生成自定义位图（BMP）和设备无关位图（DIB）图像的多功能工具集。使用此 API，您可以精确定义图像特性，如每像素位数、压缩级别和压缩类型，以满足特定需求。这个功能丰富的 API 使开发者能够轻松且灵活地创建高质量、定制化的栅格图像，适用于各种应用场景。

```csharp
public class BmpOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | 初始化 `BmpOptions` 类的新实例。 |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | 初始化 `BmpOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | 获取或设置图像的每像素位数。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Compression](../../aspose.imaging.imageoptions/bmpoptions/compression/) { get; set; } | 获取或设置压缩类型。默认压缩类型是 Bitfields，它允许保存带透明度的 [`BmpImage`](../../aspose.imaging.fileformats.bmp/bmpimage/)。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | 创建此实例的成员逐一克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | 尝试设置一个 *metadata* 实例，如果此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 实例。 |

## 示例

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

此示例演示了如何使用 SaveOptions 命名空间中的不同类进行导出。将 Gif 类型的图像加载到 Image 实例中，然后导出为多种格式。

```csharp
[C#]

string dir = "c:\\temp\\";

//在 Image 类的实例中加载现有的 Gif 类型图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //使用默认选项导出为 BMP 文件格式。
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //使用默认选项导出为 JPEG 文件格式。
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //使用默认选项导出为 PNG 文件格式。
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //使用默认选项导出为 TIFF 文件格式。
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

以下示例展示了如何在不针对特定图像类型的情况下，以通用方式将多页矢量图像转换为 BMP 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.bmp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 仅导出前两页。实际上，由于 BMP 不是多页格式，只会光栅化一页。
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### 另请参见

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


