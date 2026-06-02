---
title: "接口 IMaskingLayer"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Masking.Result.IMaskingLayer 接口。遮罩层。"
type: docs
weight: 11080
url: /zh/net/aspose.imaging.masking.result/imaskinglayer/
---
## IMaskingLayer interface

掩码层

```csharp
public interface IMaskingLayer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ObjectNumber](../../aspose.imaging.masking.result/imaskinglayer/objectnumber/) { get; } | 获取对象编号。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetImage](../../aspose.imaging.masking.result/imaskinglayer/getimage/)() | 提供结果图像。 |
| [GetMask](../../aspose.imaging.masking.result/imaskinglayer/getmask/)() | 获取图像掩码。 |

## 示例

本示例展示了如何使用图像掩码和 K 均值分割算法将光栅图像分解为多个图像。图像掩码是一种用于将背景与前景图像对象分离的图像处理技术。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // 设置簇的数量（分离的对象）。默认值为 2，即前景对象和背景。
    args.NumberOfObjects = 3;

    // 设置最大迭代次数。
    args.MaxIterationNumber = 50;

    // 设置分割方法的精度（可选）。
    args.Precision = 1;
        
    // 每个簇（段）将保存为单独的 PNG 文件。
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // 使用 K 均值聚类。
    // K 均值聚类允许将图像拆分为多个独立的簇（段）。
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // 背景颜色将为橙色。
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // 从掩码结果中获取图像并保存为 PNG。
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

使用分段掩码加速分割过程

```csharp
[C#]

// 掩码导出选项
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// 使用 GraphCut 聚类。
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// 背景颜色将变为透明。
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // 减小图像尺寸以加速分割过程
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // 获取前景掩码
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // 将掩码大小增至原始图像的尺寸
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // 将掩码应用于原始图像以获得前景段
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

本示例展示了如何使用图像掩码和手动掩码将光栅图像分解为多个图像。图像掩码是一种用于将背景与前景图像对象分离的图像处理技术。

```csharp
[C#]

string dir = "c:\\temp\\";

// 定义手动掩码。
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// 每个簇（段）将保存为单独的 PNG 文件。
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// 设置手动掩码。
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // 使用手动聚类算法。
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // 组成掩码的所有形状将合并为一个。
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // 背景颜色将为橙色。
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // 将对源图像应用掩码的区域。
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // 从掩码结果中获取图像并保存为 PNG。
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

本示例展示了如何为图像掩码算法指定建议，以提高分割（聚类）方法的精度。图像掩码是一种用于将背景与前景图像对象分离的图像处理技术。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // 建议 #1。
    // 对图像进行目视分析并设置感兴趣区域。分割结果将仅包含完全位于该区域内的对象。
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // 建议 #2。
    // 对图像进行视觉分析并设置属于分离对象的点。
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // 每个簇（段）将保存为单独的 PNG 文件。
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // 使用 GraphCut 聚类。
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // 背景颜色将为橙色。
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // 从掩码结果中获取图像并保存为 PNG。
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Gorilla.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

将遮罩会话保存到文件，以便长时间会话以及在其他环境中恢复会话的可能性。

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// 掩码导出选项
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// 使用 GraphCut 聚类。
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// 背景颜色将为橙色。
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// 首次启动会话并保存到文件
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// 从文件恢复遮罩会话
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // 对图像进行视觉分析并设置属于分离对象的点。
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // 显式转移导出选项，因为它不可序列化
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### 另请参见

* namespace [Aspose.Imaging.Masking.Result](../../aspose.imaging.masking.result/)
* assembly [Aspose.Imaging](../../)


