---
title: "RasterImage.GetPixel"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。获取图像像素。"
type: docs
weight: 360
url: /zh/net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

获取图像像素。

```csharp
public Color GetPixel(int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 像素的 x 坐标。 |
| y | Int32 | 像素的 y 坐标。 |

### 返回值

指定位置的像素颜色。

## 示例

以下示例加载栅格图像并获取任意像素的颜色。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 获取图像左上角像素的颜色。
    Color color = rasterImage.GetPixel(0, 0);

    // 获取各个颜色分量的值
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### 另请参见

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


