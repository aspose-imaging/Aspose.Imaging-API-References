---
title: GifOptions
second_title: Aspose.Imaging for .NET API 参考
description: gif 文件格式创建选项
type: docs
weight: 10000
url: /zh/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

gif 文件格式创建选项。

```csharp
public class GifOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | 初始化[`GifOptions`](../gifoptions)类. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | 初始化[`GifOptions`](../gifoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | 获取或设置背景颜色。 |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | 获取或设置 GIF 背景颜色索引。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | 获取或设置 GIF 颜色分辨率。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | 获取或设置一个指示是否应用调色板校正的值。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | 获取或设置一个值，表示 GIF 是否有预告片。 |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | 获取或设置GIF图像是否具有透明色的值。 |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | 如果图像应该隔行扫描，则为真。 |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | 获取或设置一个值，指示是否对调色板条目进行排序。 |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | 获取或设置循环计数（默认为 1 个循环） |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | 获取或设置允许的最大像素差。如果大于零，将使用有损压缩。 最佳有损压缩的推荐值为 80。30 是非常轻的压缩，200 是重的。 当只引入少量损失时效果最好，并且由于压缩算法的限制非常高的损失水平不会带来太大的收益。 允许值的范围是[0, 1000]。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | 获取或设置调色板。 |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | 获取或设置 GIF 像素纵横比。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | 获取或设置要在其中创建图像的源。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |

### 例子

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

以下示例显示了如何在不引用特定图像类型的情况下以一般方式将多页矢量图像转换为 GIF 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 只导出前两页。这些页面将在输出 GIF 中显示为动画帧。
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

这个例子展示了如何在颜色类型的数组中加载像素信息，操作数组并将其设置回图像。为了执行这些操作，这个例子创建了一个新的 Image 文件（GIF 格式）uisng MemoryStream 对象。

```csharp
[C#]

//创建一个MemoryStream实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建一个 GifOptions 实例并设置它的各种属性，包括 Source 属性
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建一个Image实例
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //通过指定区域为图像边界来获取图像的像素
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置alrenative索引像素的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //设置索引像素颜色为黄色
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //设置索引像素颜色为蓝色
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //将像素变化应用到图像
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

### 也可以看看

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* 命名空间 [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
