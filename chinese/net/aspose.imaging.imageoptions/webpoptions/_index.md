---
title: "类 WebPOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.WebPOptions 类。使用我们的 API 创建现代 WebP 栅格网页图像，提供对无损和有损压缩以及 alpha 通道和动画循环的强大支持。通过动态视觉效果增强您的网页内容，同时优化文件大小以提升加载速度和用户体验。"
type: docs
weight: 10660
url: /zh/net/aspose.imaging.imageoptions/webpoptions/
---
## WebPOptions class

使用我们的 API 创建现代 WebP 栅格网页图像，提供对无损和有损压缩、Alpha 通道以及动画循环的强大支持。通过动态视觉效果提升网页内容，同时优化文件大小以改善加载速度和用户体验。

```csharp
public class WebPOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WebPOptions](webpoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnimBackgroundColor](../../aspose.imaging.imageoptions/webpoptions/animbackgroundcolor/) { get; set; } | 获取或设置动画背景的颜色。 |
| [AnimLoopCount](../../aspose.imaging.imageoptions/webpoptions/animloopcount/) { get; set; } | 获取或设置动画循环次数。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [Lossless](../../aspose.imaging.imageoptions/webpoptions/lossless/) { get; set; } | 获取或设置一个值，指示此 `WebPOptions` 是否为无损。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| [Quality](../../aspose.imaging.imageoptions/webpoptions/quality/) { get; set; } | 获取或设置质量。 |
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

此示例展示了如何使用不同的压缩质量从另一幅栅格图像创建 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载 GIF 动画
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // 对于无损压缩，提升质量设置会提高压缩质量并减小文件大小
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // file size: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // file size: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // file size: 40 KB


    // 对于有损压缩，提升 Quality 值会提升图像质量并增大文件大小
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // file size: 24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // file size: 36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // file size: 51 KB
}
```

以下示例展示了如何在不引用特定图像类型的情况下，将多页矢量图像转换为 WEBP 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.webp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.WebPOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 仅导出前两页。这些页面将在输出的 WEBP 中作为动画帧呈现。
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


