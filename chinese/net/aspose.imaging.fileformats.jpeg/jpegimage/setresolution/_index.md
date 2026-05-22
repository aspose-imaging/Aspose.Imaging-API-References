---
title: "JpegImage.SetResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegImage 方法。为指定的 RasterImage 设置分辨率，以确保准确的缩放和打印能力。此方法使用户能够根据其特定需求（无论是数字显示还是实体复制）定制图像分辨率。通过设置分辨率，用户可以优化图像质量并确保与各种输出设备和介质的兼容性，从而提升整体视觉体验和图像的可用性。"
type: docs
weight: 210
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/setresolution/
---
## JpegImage.SetResolution method

为指定的 [`RasterImage`](../../../aspose.imaging/rasterimage/) 设置分辨率，以确保准确的缩放和打印能力。此方法使用户能够根据其特定需求（无论是数字显示还是实体复制）定制图像分辨率。通过设置分辨率，用户可以优化图像质量并确保与各种输出设备和介质的兼容性，提升整体视觉体验和图像的可用性。

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | Double | [`RasterImage`](../../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸点数）。 |
| dpiY | Double | [`RasterImage`](../../../aspose.imaging/rasterimage/) 的垂直分辨率（每英寸点数）。 |

## 示例

以下示例展示了如何设置 JPEG 图像的水平/垂直分辨率。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)image;

    // 获取 BmpImage 的水平和垂直分辨率
    double horizontalResolution = jpegImage.HorizontalResolution;
    double verticalResolution = jpegImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpegImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpegImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpegImage.VerticalResolution);
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

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


