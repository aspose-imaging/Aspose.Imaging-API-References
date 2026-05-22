---
title: "IMaskingLayer.ObjectNumber"
second_title: "Aspose.Imaging for .NET API 参考"
description: "IMaskingLayer 属性。 获取对象编号"
type: docs
weight: 10
url: /zh/net/aspose.imaging.masking.result/imaskinglayer/objectnumber/
---
## IMaskingLayer.ObjectNumber property

获取对象编号。

```csharp
public int ObjectNumber { get; }
```

### Property Value

对象编号。

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

### 另请参见

* interface [IMaskingLayer](../)
* namespace [Aspose.Imaging.Masking.Result](../../imaskinglayer/)
* assembly [Aspose.Imaging](../../../)


