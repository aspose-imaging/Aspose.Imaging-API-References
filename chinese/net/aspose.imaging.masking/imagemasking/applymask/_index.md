---
title: "ImageMasking.ApplyMask"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageMasking 方法。将掩码应用于指定的源图像。"
type: docs
weight: 60
url: /zh/net/aspose.imaging.masking/imagemasking/applymask/
---
## ImageMasking.ApplyMask method

将遮罩应用于指定的源图像。

```csharp
public static void ApplyMask(RasterImage targetImage, RasterImage mask, 
    MaskingOptions maskingOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetImage | RasterImage | 目标图像。 |
| 掩码 | RasterImage | 要应用的掩码图像。 |
| maskingOptions | MaskingOptions | 掩码选项。 |

## 示例

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

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [MaskingOptions](../../../aspose.imaging.masking.options/maskingoptions/)
* class [ImageMasking](../)
* namespace [Aspose.Imaging.Masking](../../imagemasking/)
* assembly [Aspose.Imaging](../../../)


