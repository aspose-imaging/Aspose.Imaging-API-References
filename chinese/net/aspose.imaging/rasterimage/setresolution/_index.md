---
title: "RasterImage.SetResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。设置此 RasterImage 的分辨率"
type: docs
weight: 650
url: /zh/net/aspose.imaging/rasterimage/setresolution/
---
## RasterImage.SetResolution method

为此 [`RasterImage`](../) 设置分辨率。

```csharp
public virtual void SetResolution(double dpiX, double dpiY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | Double | [`RasterImage`](../) 的水平分辨率（每英寸点数）。 |
| dpiY | Double | [`RasterImage`](../) 的垂直分辨率（每英寸点数）。 |

## 示例

以下示例展示如何设置光栅图像的水平/垂直分辨率。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 获取图像的水平和垂直分辨率
    double horizontalResolution = rasterImage.HorizontalResolution;
    double verticalResolution = rasterImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.Console.WriteLine("Set resolution values to 96 dpi");
        rasterImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", rasterImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", rasterImage.VerticalResolution);
    }

    // 输出可能如下所示：
    // 水平分辨率（每英寸像素）：300
    // 垂直分辨率（每英寸像素）：300
    // 将分辨率值设置为 96 dpi
    // 水平分辨率（每英寸像素）：96
    // 垂直分辨率（每英寸像素）：96
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


