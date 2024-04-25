---
title: BmpOptions
second_title: Aspose.Imaging for .NET API 参考
description: bmp 文件格式创建选项
type: docs
weight: 9910
url: /zh/aspose.imaging.imageoptions/bmpoptions/
---
## BmpOptions class

bmp 文件格式创建选项。

```csharp
public class BmpOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [BmpOptions](bmpoptions#constructor)() | 初始化[`BmpOptions`](../bmpoptions)类. |
| [BmpOptions](bmpoptions#constructor_1)(BmpOptions) | 初始化[`BmpOptions`](../bmpoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/bmpoptions/bitsperpixel) { get; set; } | 获取或设置每像素计数的图像位数。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Compression](../../aspose.imaging.imageoptions/bmpoptions/compression) { get; set; } | 获取或设置压缩。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | 获取或设置调色板。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | 获取或设置要在其中创建图像的源。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |

### 例子

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

此示例演示了将 SaveOptions 命名空间中的不同类用于导出目的。将 Gif 类型的图像加载到 Image 的实例中，然后导出为多种格式。

```csharp
[C#]

string dir = "c:\\temp\\";

//在 Image 类的实例中加载现有图像（Gif 类型）
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //使用默认选项导出为BMP文件格式
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //使用默认选项导出为JPEG文件格式
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //使用默认选项导出为PNG文件格式
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //使用默认选项导出为 TIFF 文件格式
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

以下示例显示了如何在不引用特定图像类型的情况下以一般方式将多页矢量图像转换为 BMP 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.bmp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 只导出前两页。事实上，只有一页会被光栅化，因为 BMP 不是多页格式。
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

### 也可以看看

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* 命名空间 [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
