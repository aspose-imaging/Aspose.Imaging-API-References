---
title: "RasterImage.SetArgb32Pixel"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。为指定位置设置图像的 32 位 ARGB 像素"
type: docs
weight: 620
url: /zh/net/aspose.imaging/rasterimage/setargb32pixel/
---
## RasterImage.SetArgb32Pixel method

为指定位置设置图像的 32 位 ARGB 像素。

```csharp
public void SetArgb32Pixel(int x, int y, int argb32Color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 像素的 x 坐标。 |
| y | Int32 | 像素的 y 坐标。 |
| argb32Color | Int32 | 指定位置的 32 位 ARGB 像素。 |

## 示例

以下示例加载光栅图像，并设置任意像素的颜色。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 设置左上角像素的颜色。
    rasterImage.SetArgb32Pixel(0, 0, Aspose.Imaging.Color.Aqua.ToArgb());

    // 另一种方法是直接传递 Aspose.Imaging.Color 的实例
    rasterImage.SetPixel(0, 0, Aspose.Imaging.Color.Aqua);
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


