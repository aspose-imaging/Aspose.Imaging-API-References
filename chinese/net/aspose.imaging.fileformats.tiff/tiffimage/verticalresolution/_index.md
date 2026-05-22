---
title: "TiffImage.VerticalResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 属性。以每英寸像素为单位访问指定 Image 的垂直分辨率，实现精确的调整和渲染优化。轻松利用关键图像数据，简化图像处理工作流，确保在应用程序中获得卓越的质量和性能。"
type: docs
weight: 110
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/verticalresolution/
---
## TiffImage.VerticalResolution property

以每英寸像素为单位访问指定的 [`Image`](../../../aspose.imaging/image/) 的垂直分辨率，实现精确的调整和渲染优化。轻松利用关键图像数据，简化图像处理工作流，确保在您的应用程序中获得卓越的质量和性能。

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

垂直分辨率。

## 备注

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

## 示例

以下示例展示了如何设置 TIFF 图像的水平/垂直分辨率。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 获取 TiffImage 的水平和垂直分辨率。
    double horizontalResolution = tiffImage.HorizontalResolution;
    double verticalResolution = tiffImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.Console.WriteLine("Set resolution values to 96 dpi");
        tiffImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", tiffImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", tiffImage.VerticalResolution);
    }
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


