---
title: "JpegImage.VerticalResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegImage 属性。此属性管理关联 RasterImage 的垂直分辨率，以每英寸像素数表示。调整此分辨率会影响图像在打印或以固定物理尺寸显示时的大小和质量。通过设置此属性，您可以控制图像像素在垂直方向上的密集程度，从而影响整体的清晰度和锐度。"
type: docs
weight: 160
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution/
---
## JpegImage.VerticalResolution property

此属性管理关联的 [`RasterImage`](../../../aspose.imaging/rasterimage/) 的垂直分辨率，以每英寸像素数表示。调整此分辨率会影响图像在打印或以固定物理尺寸显示时的大小和质量。通过设置此属性，您可以控制图像像素在垂直方向上的密集程度，从而影响整体的清晰度和锐度。

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

垂直分辨率。

## 备注

注意，默认情况下此值始终为 72，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

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


