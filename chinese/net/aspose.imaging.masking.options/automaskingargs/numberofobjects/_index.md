---
title: "AutoMaskingArgs.NumberOfObjects"
second_title: "Aspose.Imaging for .NET API 参考"
description: "AutoMaskingArgs 属性。获取或设置要将初始图像分离的对象数量（可选），默认值为 2（对象和背景）"
type: docs
weight: 30
url: /zh/net/aspose.imaging.masking.options/automaskingargs/numberofobjects/
---
## AutoMaskingArgs.NumberOfObjects property

获取或设置要将初始图像分割成的对象数量（可选），默认值为 2（对象和背景）。

```csharp
public int NumberOfObjects { get; set; }
```

### Property Value

对象数量。

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

### 另请参见

* class [AutoMaskingArgs](../)
* namespace [Aspose.Imaging.Masking.Options](../../automaskingargs/)
* assembly [Aspose.Imaging](../../../)


