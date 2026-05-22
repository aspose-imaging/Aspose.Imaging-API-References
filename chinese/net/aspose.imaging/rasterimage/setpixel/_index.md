---
title: "RasterImage.SetPixel"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。为指定位置设置图像像素"
type: docs
weight: 640
url: /zh/net/aspose.imaging/rasterimage/setpixel/
---
## RasterImage.SetPixel method

为指定位置设置图像像素。

```csharp
public void SetPixel(int x, int y, Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 像素的 x 坐标。 |
| y | Int32 | 像素的 y 坐标。 |
| 颜色 | 颜色 | 指定位置的像素颜色。 |

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

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


