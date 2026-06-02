---
title: "RasterCachedImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedImage 方法。调整图像亮度"
type: docs
weight: 20
url: /zh/net/aspose.imaging/rastercachedimage/adjustbrightness/
---
## RasterCachedImage.AdjustBrightness method

调整图像的亮度。

```csharp
public override void AdjustBrightness(int brightness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | Int32 | 亮度值。 |

## 示例

以下示例对栅格缓存图像执行亮度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // 设置亮度值。亮度的接受范围为 [-255, 255]。
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### 另请参见

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


