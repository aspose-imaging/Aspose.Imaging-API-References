---
title: Decompose
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置一个值该值指示 是否无需将每个 Shape 与蒙版分离为单独的对象或作为与背景分离的蒙版的联合对象
type: docs
weight: 40
url: /zh/net/aspose.imaging.masking.options/maskingoptions/decompose/
---
## MaskingOptions.Decompose property

获取或设置一个值，该值指示 是否无需将每个 Shape 与蒙版分离为单独的对象或作为与背景分离的蒙版的联合对象。

```csharp
public bool Decompose { get; set; }
```

### 适当的价值

` true` 如果分解；否则，` false` 。

### 例子

此示例说明如何使用图像遮罩和手动遮罩将光栅图像分解为多个图像。图像遮罩是一种图像处理技术，用于将背景与前景图像对象分开。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 定义一个手动掩码。
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

    // 每个簇（段）将被存储到一个单独的 PNG 文件中。
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    // 设置手动掩码.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

        // 使用手动聚类算法.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // 构成蒙版的所有形状都将合并为一个。 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

        // 背景颜色为橙色。
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

        // 将应用遮罩的源图像区域。
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

        // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

        // 将源图像分成若干簇（段）。
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
            // 从遮罩结果中获取图像并保存到PNG.
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

### 也可以看看

* class [MaskingOptions](../../maskingoptions)
* 命名空间 [Aspose.Imaging.Masking.Options](../../maskingoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->