---
title: "Image.ResizeHeightProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。按比例调整高度。使用默认的 NearestNeighbourResample。"
type: docs
weight: 270
url: /zh/net/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

按比例调整高度。默认使用 NearestNeighbourResample。

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新的高度。 |

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

按比例调整高度。

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载图像并使用各种缩放方法按比例调整大小。仅指定高度，宽度自动计算。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
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

### 另请参见

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

按比例调整高度。

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 图像缩放设置。 |

### 另请参见

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


