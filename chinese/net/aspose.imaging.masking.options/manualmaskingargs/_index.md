---
title: "类 ManualMaskingArgs"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Masking.Options.ManualMaskingArgs 类。表示手动掩模方法指定的参数"
type: docs
weight: 11050
url: /zh/net/aspose.imaging.masking.options/manualmaskingargs/
---
## ManualMaskingArgs class

表示手动遮罩方法指定的参数

```csharp
public class ManualMaskingArgs : IMaskingArgs
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ManualMaskingArgs](manualmaskingargs/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Mask](../../aspose.imaging.masking.options/manualmaskingargs/mask/) { get; set; } | 获取或设置构成掩模的图形形状集合。 |

## 示例

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

### 另请参见

* interface [IMaskingArgs](../imaskingargs/)
* namespace [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options/)
* assembly [Aspose.Imaging](../../)


