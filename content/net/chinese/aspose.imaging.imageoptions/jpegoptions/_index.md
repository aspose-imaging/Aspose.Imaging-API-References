---
title: JpegOptions
second_title: Aspose.Imaging for .NET API 参考
description: jpeg 文件格式创建选项
type: docs
weight: 10030
url: /zh/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

jpeg 文件格式创建选项。

```csharp
public class JpegOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | 初始化[`JpegOptions`](../jpegoptions)类. |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | 初始化[`JpegOptions`](../jpegoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BitsPerChannel](../../aspose.imaging.imageoptions/jpegoptions/bitsperchannel) { get; set; } | 获取或设置无损 jpeg 图像的每个通道的位。现在我们支持每通道 2 到 8 位。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [CmykColorProfile](../../aspose.imaging.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | CMYK jpeg 图像的目标 CMYK 颜色配置文件。用于保存图像。必须与 RGBColorProfile 配对以进行正确的颜色转换。 |
| [ColorType](../../aspose.imaging.imageoptions/jpegoptions/colortype) { get; set; } | 获取或设置 jpeg 图像的颜色类型。 |
| [Comment](../../aspose.imaging.imageoptions/jpegoptions/comment) { get; set; } | 获取或设置jpeg文件注释。 |
| [CompressionType](../../aspose.imaging.imageoptions/jpegoptions/compressiontype) { get; set; } | 获取或设置压缩类型。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [ExifData](../../aspose.imaging.imageoptions/jpegoptions/exifdata) { get; set; } | 获取或设置exif数据容器 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]. |
| [HorizontalSampling](../../aspose.imaging.imageoptions/jpegoptions/horizontalsampling) { get; set; } | 获取或设置每个分量的水平二次采样。 |
| [Jfif](../../aspose.imaging.imageoptions/jpegoptions/jfif) { get; set; } | 获取或设置 jfif. |
| [JpegLsAllowedLossyError](../../aspose.imaging.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | 获取或设置用于近无损编码的 JPEG-LS 差异界限（JPEG-LS 规范中的 NEAR 参数）。 |
| [JpegLsInterleaveMode](../../aspose.imaging.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | 获取或设置 JPEG-LS 交错模式。 |
| [JpegLsPreset](../../aspose.imaging.imageoptions/jpegoptions/jpeglspreset) { get; set; } | 获取或设置JPEG-LS预设参数。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | 获取或设置调色板。 |
| [PreblendAlphaIfPresent](../../aspose.imaging.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | 获取或设置一个值，该值指示红色、绿色和蓝色分量是否应与背景颜色混合，如果存在 alpha 通道。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| [Quality](../../aspose.imaging.imageoptions/jpegoptions/quality) { get; set; } | 获取或设置图像质量。 |
| [RdOptSettings](../../aspose.imaging.imageoptions/jpegoptions/rdoptsettings) { get; set; } | 获取或设置 RD 优化器设置。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [ResolutionUnit](../../aspose.imaging.imageoptions/jpegoptions/resolutionunit) { get; set; } | 获取或设置分辨率单位。 |
| [RgbColorProfile](../../aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | CMYK jpeg 图像的目标 RGB 颜色配置文件。用于保存图像。必须与 CMYKColorProfile 配对以进行正确的颜色转换。 |
| [SampleRoundingMode](../../aspose.imaging.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | 获取或设置样本舍入模式以将 8 位值适合 n 位值。BitsPerChannel |
| [ScaledQuality](../../aspose.imaging.imageoptions/jpegoptions/scaledquality) { get; } | 缩放质量。 |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | 获取或设置要在其中创建图像的源。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| [VerticalSampling](../../aspose.imaging.imageoptions/jpegoptions/verticalsampling) { get; set; } | 获取或设置每个分量的垂直二次采样。 |
| override [XmpData](../../aspose.imaging.imageoptions/jpegoptions/xmpdata) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |

### 例子

这个例子演示了使用 System.IO.Stream 创建一个新的 Image 文件（JPEG 类型）

```csharp
[C#]

//创建一个 JpegOptions 实例并设置它的各种属性
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//创建System.IO.Stream的实例
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//定义JpegOptions实例的源属性
//第二个布尔参数确定Stream一旦超出范围就被释放
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//创建一个Image实例，调用Create方法以JpegOptions为参数初始化Image对象   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //做一些图像处理
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

以下示例显示了如何在不引用特定图像类型的情况下以一般方式将多页矢量图像转换为 JPEG 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.jpeg");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 只导出前两页。事实上，只有一页会被光栅化，因为 JPEG 不是多页格式。
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
