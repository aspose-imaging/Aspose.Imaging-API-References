---
title: "类 PngOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.PngOptions 类。使用我们的 API，轻松创建高质量的便携式网络图形（PNG）光栅图像，提供可自定义的压缩级别、每像素位深、颜色深度和 Alpha 位等选项。无缝处理 XMP 元数据容器，确保全面的图像元数据管理，并使您能够轻松地将 PNG 图像定制到精确的规格要求。"
type: docs
weight: 10510
url: /zh/net/aspose.imaging.imageoptions/pngoptions/
---
## PngOptions class

使用我们的 API 轻松创建高质量的便携式网络图形 (PNG) 栅格图像，提供可自定义的压缩级别、每像素位深度和 Alpha 位选项。无缝处理 XMP 元数据容器，确保完整的图像元数据管理，使您能够轻松地将 PNG 图像定制到精确的规格要求。

```csharp
public class PngOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | 初始化 `PngOptions` 类的新实例。 |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | 初始化 `PngOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth/) { get; set; } | 获取或设置位深度值，范围为 1、2、4、8、16。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype/) { get; set; } | 获取或设置颜色的类型。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype/) { get; set; } | 获取或设置在 png 文件保存过程中使用的过滤器类型。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [PngCompressionLevel](../../aspose.imaging.imageoptions/pngoptions/pngcompressionlevel/) { get; set; } | 获取或设置 [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) 的压缩级别。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive/) { get; set; } | 获取或设置一个值，指示 [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) 是否为渐进式。 |
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

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.imaging.imageoptions/pngoptions/defaultcompressionlevel/) | 默认压缩级别。 |

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

以下示例展示了如何在不针对特定图像类型的情况下，将多页矢量图像通用地转换为 PNG 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.png");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 仅导出前两页。实际上，由于 PNG 不是多页格式，只会对一页进行光栅化。
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

此示例使用 Graphics 类在 Image 表面创建基本形状。为了演示操作，示例创建一个 PNG 格式的新 Image，并使用 Graphics 类提供的 Draw 方法在 Image 表面绘制基本形状。

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建 PngOptions 的实例并设置其各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //为 PngOptions 设置 Source
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化 Graphics 类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除 Graphics 表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色的 Pen 对象绘制弧线，
        //一个围绕弧线的 Rectangle、起始角度和扫掠角度
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色的 Pen 对象和坐标点绘制贝塞尔曲线。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和围绕的 Rectangle 绘制椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //绘制直线
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //绘制饼图扇形
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //绘制矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建 SolidBrush 对象并设置其各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和 Font 在特定点绘制字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 另请参见

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


