---
title: ResizeHeightProportionally
second_title: Aspose.Imaging for .NET API 参考
description: 按比例调整高度默认NearestNeighbourResample已使用
type: docs
weight: 210
url: /zh/net/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

按比例调整高度。默认NearestNeighbourResample已使用。

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新高度。 |

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

按比例调整高度。

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新高度。 |
| resizeType | ResizeType | 调整大小的类型。 |

### 例子

此示例加载图像并使用各种调整大小方法按比例调整其大小。仅指定高度，自动计算宽度。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

使用分段掩码加快分段过程

```csharp
[C#]

// 屏蔽导出选项
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// 使用 GraphCut 聚类。
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// 背景颜色将是透明的。
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // 减小图像大小以加快分割过程
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // 将源图像分成几个簇（段）。
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // 获取前景蒙版
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // 将蒙版的大小增加到原始图像的大小
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

### 也可以看看

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

按比例调整高度。

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新高度。 |
| settings | ImageResizeSettings | 图像调整大小设置。 |

### 也可以看看

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
