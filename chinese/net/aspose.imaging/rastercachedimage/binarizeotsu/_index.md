---
title: "RasterCachedImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedImage 方法。使用 Otsu 阈值对图像进行二值化"
type: docs
weight: 90
url: /zh/net/aspose.imaging/rastercachedimage/binarizeotsu/
---
## RasterCachedImage.BinarizeOtsu method

使用 Otsu 阈值法对图像进行二值化

```csharp
public override void BinarizeOtsu()
```

## 示例

以下示例使用 Otsu 阈值对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // 使用 Otsu 阈值化对图像进行二值化。
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### 另请参见

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


