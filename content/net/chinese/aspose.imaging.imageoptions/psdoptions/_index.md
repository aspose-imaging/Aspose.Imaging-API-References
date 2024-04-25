---
title: PsdOptions
second_title: Aspose.Imaging for .NET API 参考
description: psd文件格式创建选项.
type: docs
weight: 10140
url: /zh/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

psd文件格式创建选项.

```csharp
public class PsdOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | 初始化[`PsdOptions`](../psdoptions)类. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | 初始化[`PsdOptions`](../psdoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | 获取或设置每个颜色通道的位数。 |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | 获取或设置颜色通道数。 |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | 获取或设置psd颜色模式。 |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | 获取或设置psd压缩方式 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | 获取或设置调色板。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | 获取或设置文件格式版本。它可以是 PSD 或 PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | 获取或设置一个值，指示是否 [刷新图像预览数据] - 用于最大限度地与其他 PSD 图像查看器兼容的选项。 请注意，Compact Framework 平台不支持将文本图层绘制到最终布局 |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | 获取或设置一个值，该值指示是否 - 删除全局文本引擎资源 - 用于一些文本分层的 psd 文件，仅在处理后无法在 Adobe Photoshop 中打开的情况下使用（主要是与缺少字体的文本图层相关）。 使用此选项后，用户需要在 Photoshop 文件中打开下一个：菜单“文本”-&gt;“处理不存在的字体”。在该操作之后，所有文本将再次出现。 请注意，此操作可能会导致一些最终布局更改。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | 获取或设置要在其中创建图像的源。 |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | 获取或设置 PSD 矢量化选项。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | 获取或设置psd文件版本。 |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | 获取或设置 XMP 数据容器 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |

### 例子

此示例演示了使用 Aspsoe.Imaging for .Net API 将图像转换为 PSD 格式。为了实现这个目标，这个例子加载了一个现有的图像，然后将它保存回 PSD 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

//创建一个图像类的实例，并通过文件路径使用现有文件对其进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //创建一个PsdOptions类的实例
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //设置CompressionMethod为RLE
    //注意：其他支持的CompressionMethod是CompressionMethod.RAW [无压缩]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //设置颜色模式为灰度
    //注意：其他支持的ColorModes有ColorModes.Bitmap和ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //使用提供的 PsdOptions 设置将图像保存到磁盘位置
    image.Save(dir + "output.psd", psdOptions);
}
```

以下示例显示了如何在不引用特定图像类型的情况下以一般方式将多页矢量图像转换为 PSD 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 只导出前两页。这些页面将在输出 PSD 中显示为图层。
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
