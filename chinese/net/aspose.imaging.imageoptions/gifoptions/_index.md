---
title: "类 GifOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.GifOptions 类。用于创建图形交换格式（GIF）光栅图像文件的 API 为开发者提供了全面的选项，以精确控制生成 GIF 图像。该 API 具备设置背景颜色、颜色调色板、分辨率、交错类型、透明颜色、XMP 元数据容器以及图像压缩等功能，确保在满足特定应用需求的同时，实现灵活高效的优化和视觉上令人满意的 GIF 创建。"
type: docs
weight: 10350
url: /zh/net/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Graphical Interchange Format（GIF）栅格图像文件创建的 API 为开发者提供了生成 GIF 图像的全面选项，可实现精确控制。通过设置背景颜色、颜色调色板、分辨率、交错类型、透明颜色、XMP 元数据容器以及图像压缩等功能，此 API 确保在创建针对特定应用需求的优化且视觉上吸引人的 GIF 时具备灵活性和高效性。

```csharp
public class GifOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | 初始化 `GifOptions` 类的新实例。 |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | 初始化 `GifOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | 获取或设置 GIF 背景颜色索引。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution/) { get; set; } | 获取或设置 GIF 颜色分辨率。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | 获取或设置指示是否应用调色板校正的值。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer/) { get; set; } | 获取或设置指示 GIF 是否具有尾部的值。 |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor/) { get; set; } | 获取或设置一个值，指示 GIF 图像是否具有透明颜色。如果返回值为 `null`，则此属性被源图像上下文覆盖。 |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced/) { get; set; } | 如果图像应交错，则为 true。 |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted/) { get; set; } | 获取或设置一个值，指示调色板条目是否已排序。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount/) { get; set; } | 获取或设置循环计数（默认 1 次循环） |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff/) { get; set; } | 获取或设置允许的最大像素差异。如果大于零，将使用有损压缩。推荐的最佳有损压缩值为 80。30 表示非常轻微的压缩，200 表示较重的压缩。该设置在仅引入少量损失时效果最佳，由于压缩算法的限制，极高的损失水平不会带来太多收益。允许的取值范围为 [0, 1000]。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | 获取或设置 GIF 像素宽高比。 |
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

以下示例展示了如何以通用方式将多页矢量图像转换为 GIF 格式，而无需引用特定的图像类型。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 仅导出前两页。这些页面将在输出的 GIF 中作为动画帧呈现。
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

本示例展示了如何将像素信息加载到 Color 类型的数组中，操作该数组并将其设置回图像。为执行这些操作，示例使用 MemoryStream 对象创建一个新的（GIF 格式）图像文件。

```csharp
[C#]

//创建 MemoryStream 的实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 GifOptions 的实例并设置其各种属性，包括 Source 属性
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //通过将区域指定为图像边界来获取图像像素
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置交替索引像素的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //将索引像素颜色设置为黄色
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //将索引像素颜色设置为蓝色
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //将像素更改应用到图像
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

    // 将 MemoryStream 写入文件
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### 另请参见

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


