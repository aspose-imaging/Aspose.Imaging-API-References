---
title: "RasterImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。图像对比度调整"
type: docs
weight: 190
url: /zh/net/aspose.imaging/rasterimage/adjustcontrast/
---
## RasterImage.AdjustContrast method

图像对比度。

```csharp
public virtual void AdjustContrast(float contrast)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | 单精度 | 对比度值（范围为 [-100; 100]） |

## 示例

以下示例对图像执行对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 设置对比度值。对比度的接受范围为 [-100f, 100f]。
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


