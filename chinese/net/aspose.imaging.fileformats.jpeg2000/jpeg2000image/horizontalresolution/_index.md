---
title: "Jpeg2000Image.HorizontalResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Jpeg2000Image 属性。此属性允许检索或修改 RasterImage 的水平分辨率，单位为每英寸像素 (PPI)。调整此分辨率可能影响图像在打印或显示时的尺寸和质量。通过设置水平分辨率，用户可以针对特定的输出设备或应用程序优化图像，确保获得最佳的视觉效果。"
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/horizontalresolution/
---
## Jpeg2000Image.HorizontalResolution property

此属性允许检索或修改 [`RasterImage`](../../../aspose.imaging/rasterimage/) 的水平分辨率，单位为每英寸像素 (PPI)。调整此分辨率可能影响图像在打印或显示时的尺寸和质量。通过设置水平分辨率，用户可以针对特定的输出设备或应用程序优化图像，确保获得最佳的视觉效果。

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

水平分辨率。

## 备注

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

## 示例

以下示例展示了如何设置 JPEG2000 图像的水平/垂直分辨率。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jp2"))
{
    Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image)image;

    // 获取 Jpeg2000Image 的水平和垂直分辨率。
    double horizontalResolution = jpeg2000Image.HorizontalResolution;
    double verticalResolution = jpeg2000Image.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpeg2000Image.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpeg2000Image.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpeg2000Image.VerticalResolution);
    }
}
```

### 另请参见

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


