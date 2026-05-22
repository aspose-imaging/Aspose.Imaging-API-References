---
title: "类 JpegOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.JpegOptions 类。使用我们的 API 轻松创建高质量 JPEG 图像，提供可调节的压缩级别，以在不影响图像质量的情况下优化存储大小。支持多种压缩类型、近无损编码、RGB 和 CMYK 色彩配置文件，以及 EXIF、JFIF 图像数据和 XMP 容器，确保为您的图像创建需求提供多功能且可定制的选项。"
type: docs
weight: 10390
url: /zh/net/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

使用我们的 API 轻松创建高质量的 JPEG 图像，提供可调节的压缩级别，以在不影响图像质量的前提下优化存储大小。受益于对多种压缩类型、近无损编码、RGB 与 CMYK 色彩配置文件，以及 EXIF、JFIF 图像数据和 XMP 容器的支持，确保在图像创建需求中具备多样化和可定制的选项。

```csharp
public class JpegOptions : ImageOptionsBase, IHasJpegExifData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | 初始化 `JpegOptions` 类的新实例。 |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | 初始化 `JpegOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitsPerChannel](../../aspose.imaging.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | 获取或设置无损 JPEG 图像的每通道位数。现在支持 2 到 8 位每通道。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [CmykColorProfile](../../aspose.imaging.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK JPEG 图像的目标 CMYK 色彩配置文件。用于保存图像。必须与 RGBColorProfile 配对以实现正确的颜色转换。 |
| [ColorType](../../aspose.imaging.imageoptions/jpegoptions/colortype/) { get; set; } | 获取或设置 JPEG 图像的颜色类型。 |
| [Comment](../../aspose.imaging.imageoptions/jpegoptions/comment/) { get; set; } | 获取或设置 JPEG 文件注释。 |
| [CompressionType](../../aspose.imaging.imageoptions/jpegoptions/compressiontype/) { get; set; } | 获取或设置压缩类型。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging.imageoptions/jpegoptions/exifdata/) { get; set; } | 获取或设置 Exif 数据容器。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [HorizontalSampling](../../aspose.imaging.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | 获取或设置每个分量的水平子采样。 |
| [Jfif](../../aspose.imaging.imageoptions/jpegoptions/jfif/) { get; set; } | 获取或设置 jfif。 |
| [JpegLsAllowedLossyError](../../aspose.imaging.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | 获取或设置 JPEG-LS 近无损编码的差值界限（JPEG-LS 规范中的 NEAR 参数）。 |
| [JpegLsInterleaveMode](../../aspose.imaging.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | 获取或设置 JPEG-LS 交错模式。 |
| [JpegLsPreset](../../aspose.imaging.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | 获取或设置 JPEG-LS 预设参数。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [PreblendAlphaIfPresent](../../aspose.imaging.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | 获取或设置一个值，指示在存在 alpha 通道时是否应将红、绿、蓝分量与背景颜色混合。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| [Quality](../../aspose.imaging.imageoptions/jpegoptions/quality/) { get; set; } | 获取或设置图像质量。 |
| [RdOptSettings](../../aspose.imaging.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | 获取或设置 RD 优化器设置。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [ResolutionUnit](../../aspose.imaging.imageoptions/jpegoptions/resolutionunit/) { get; set; } | 获取或设置分辨率单位。 |
| [RgbColorProfile](../../aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK jpeg 图像的目标 RGB 色彩配置文件。用于保存图像。必须与 CMYKColorProfile 配对，以实现正确的颜色转换。 |
| [SampleRoundingMode](../../aspose.imaging.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 获取或设置样本四舍五入模式，以将 8 位值适配为 n 位值。BitsPerChannel |
| [ScaledQuality](../../aspose.imaging.imageoptions/jpegoptions/scaledquality/) { get; } | 缩放后的质量。 |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| [VerticalSampling](../../aspose.imaging.imageoptions/jpegoptions/verticalsampling/) { get; set; } | 获取或设置每个组件的垂直子采样。 |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | 创建此实例的成员逐一克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | 尝试设置一个 *metadata* 实例，如果此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 实例。 |

## 示例

此示例演示了使用 System.IO.Stream 创建新图像文件（JPEG 类型）。

```csharp
[C#]

//创建 JpegOptions 的实例并设置其各种属性。
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//创建 System.IO.Stream 的实例。
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//为 JpegOptions 实例定义 source 属性。
//第二个布尔参数决定在超出作用域后是否释放 Stream。
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//创建 Image 的实例，并使用 JpegOptions 作为参数调用 Create 方法来初始化 Image 对象。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //进行一些图像处理
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

以下示例展示了如何以通用方式将多页矢量图像转换为 JPEG 格式，而不针对特定图像类型。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.jpeg");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 仅导出前两页。实际上，只会光栅化一页，因为 JPEG 不是多页格式。
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
* interface [IHasJpegExifData](../../aspose.imaging.exif/ihasjpegexifdata/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


