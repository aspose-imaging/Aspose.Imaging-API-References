---
title: "RasterCachedImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedImage 方法。使用预定义阈值对图像进行二值化"
type: docs
weight: 80
url: /zh/net/aspose.imaging/rastercachedimage/binarizefixed/
---
## RasterCachedImage.BinarizeFixed method

使用预定义阈值对图像进行二值化

```csharp
public override void BinarizeFixed(byte threshold)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为255，否则为0。 |

## 示例

以下示例使用预定义阈值对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为255，否则为0。
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### 另请参见

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


