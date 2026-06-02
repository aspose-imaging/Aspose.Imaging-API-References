---
title: "RasterImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage method. 调整图像的亮度"
type: docs
weight: 180
url: /zh/net/aspose.imaging/rasterimage/adjustbrightness/
---
## RasterImage.AdjustBrightness method

调整图像的亮度。

```csharp
public virtual void AdjustBrightness(int brightness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | Int32 | 亮度值。 |

## 示例

以下示例对图像执行亮度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 设置亮度值。亮度的接受范围为 [-255, 255]。
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


