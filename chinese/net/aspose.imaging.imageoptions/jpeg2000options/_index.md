---
title: "类 Jpeg2000Options"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.Jpeg2000Options 类。使用我们的 API 创建 JPEG2000 JP2 图像文件，利用先进的小波技术对无损内容进行编码。受益于对包括有损和无损压缩在内的多种编解码器的支持，以及 XMP 元数据容器，确保多功能且高质量的图像创建，以满足您的需求。"
type: docs
weight: 10380
url: /zh/net/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

使用我们的 API 创建 JPEG2000（JP2）图像文件，利用先进的小波技术对无损内容进行编码。受益于对包括有损和无损压缩在内的多种编解码器的支持，以及 XMP 元数据容器，确保在满足您需求的同时实现多功能且高质量的图像创建。

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | 初始化 `Jpeg2000Options` 类的新实例。 |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | 初始化 `Jpeg2000Options` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec/) { get; set; } | 获取或设置 JPEG2000 编解码器 |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments/) { get; set; } | 获取或设置 JPEG 注释标记。 |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios/) { get; set; } | 获取或设置压缩比数组。为连续层提供不同的压缩比。为每个质量级别指定的比率是所需的压缩因子。需要递减的比率。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible/) { get; set; } | 获取或设置一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩（默认）。 |
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

以下示例展示了如何以通用方式将多页矢量图像转换为 JPEG 2000 格式，而不针对特定图像类型进行引用。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 仅导出前两页。实际上，由于 JPEG 2000 不是多页格式，只会光栅化一页。
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


