---
title: "RasterCachedImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedImage 方法。图像对比度调整"
type: docs
weight: 30
url: /zh/net/aspose.imaging/rastercachedimage/adjustcontrast/
---
## RasterCachedImage.AdjustContrast method

图像对比度。

```csharp
public override void AdjustContrast(float contrast)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | 单精度 | 对比度值（范围为 [-100; 100]） |

## 示例

以下示例对栅格缓存图像执行对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // 设置对比度值。对比度的接受范围为 [-100f, 100f]。
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### 另请参见

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


