---
title: "类 PsdOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.PsdOptions 类。使用我们的 API 创建 Photoshop 文档 PSD 图像，提供多种选项，包括不同的格式版本、压缩方式、颜色模式以及每个颜色通道的位数。无缝处理 XMP 元数据容器，确保全面的图像处理，利用 PSD 格式的强大功能，如图像图层、图层蒙版和文件信息，以实现设计中的自定义和创意。"
type: docs
weight: 10530
url: /zh/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

使用我们的 API 创建 Photoshop 文档 (PSD) 图像，提供多种选项，包括不同的格式版本、压缩方式、颜色模式以及每个颜色通道的位数。无缝处理 XMP 元数据容器，确保完整的图像处理，并利用 PSD 格式的功能，如图像图层、图层蒙版和文件信息，实现设计中的定制和创意。

```csharp
public class PsdOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | 初始化 `PsdOptions` 类的新实例。 |
| [PsdOptions](psdoptions/#constructor_1)(PsdOptions) | 初始化 `PsdOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount/) { get; set; } | 获取或设置每个颜色通道的位数。 |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount/) { get; set; } | 获取或设置颜色通道的数量。 |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode/) { get; set; } | 获取或设置 PSD 颜色模式。 |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod/) { get; set; } | 获取或设置 PSD 压缩方式。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion/) { get; set; } | 获取或设置文件格式版本。它可以是 PSD 或 PSB。 |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | 获取或设置一个值，指示是否 [refresh image preview data] - 该选项用于最大化与其他 PSD 图像查看器的兼容性。请注意，紧凑框架平台不支持将文本图层绘制到最终布局。 |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | 获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本层的 psd 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 "Text" -> "Process absent fonts"。该操作完成后，所有文本将再次出现。请注意，此操作可能导致一些最终布局的更改。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions/) { get; set; } | 获取或设置 PSD 矢量化选项。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version/) { get; set; } | 获取或设置 psd 文件版本。 |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata/) { get; set; } | 获取或设置 XMP 数据容器 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | 创建此实例的成员逐一克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | 尝试设置一个 *metadata* 实例，如果此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 实例。 |

## 示例

此示例演示了使用 Aspsoe.Imaging 的 .Net API 将图像转换为 PSD 格式。为实现此目标，示例加载现有图像，然后将其保存回 PSD 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

//创建 image 类的实例，并通过文件路径使用现有文件进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //创建 PsdOptions 类的实例
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //将 CompressionMethod 设置为 RLE
    //注意：其他受支持的 CompressionMethod 为 CompressionMethod.RAW【无压缩】
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //将 ColorMode 设置为 GrayScale
    //注意：其他受支持的 ColorModes 为 ColorModes.Bitmap 和 ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //使用提供的 PsdOptions 设置将图像保存到磁盘位置
    image.Save(dir + "output.psd", psdOptions);
}
```

以下示例展示了如何以通用方式将多页矢量图像转换为 PSD 格式，而不针对特定图像类型进行引用。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 仅导出前两页。这些页面将在输出的 PSD 中呈现为图层。
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


