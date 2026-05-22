---
title: "TiffImage.SetResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。为指定的 RasterImage 设置分辨率，以实现对图像渲染和显示属性的精确控制。集成此功能可优化视觉输出，并确保与各种输出设备和平台的兼容性，提升整体用户体验。"
type: docs
weight: 390
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/setresolution/
---
## TiffImage.SetResolution method

为指定的 [`RasterImage`](../../../aspose.imaging/rasterimage/) 设置分辨率，以实现对图像渲染和显示属性的精确控制。集成此功能可优化视觉输出，并确保与各种输出设备和平台的兼容性，提升整体用户体验。

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | Double | [`RasterImage`](../../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸点数）。 |
| dpiY | Double | [`RasterImage`](../../../aspose.imaging/rasterimage/) 的垂直分辨率（每英寸点数）。 |

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


