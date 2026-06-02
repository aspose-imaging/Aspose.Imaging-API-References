---
title: "TiffFrame.HorizontalResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffFrame 属性。获取或设置此 RasterImage 的水平分辨率（每英寸像素数）"
type: docs
weight: 90
url: /zh/net/aspose.imaging.fileformats.tiff/tiffframe/horizontalresolution/
---
## TiffFrame.HorizontalResolution property

获取或设置此 [`RasterImage`](../../../aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

水平分辨率。

## 示例

以下示例展示了如何设置单独 TIFF 帧的水平/垂直分辨率。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 TIFF 图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        // 获取 TiffFrame 的水平和垂直分辨率。
        double horizontalResolution = frame.HorizontalResolution;
        double verticalResolution = frame.VerticalResolution;
        System.Console.WriteLine("The horizontal resolution of frame {0}, pixels per inch: {1}", i, horizontalResolution);
        System.Console.WriteLine("The vertical resolution, of frame {0}, pixels per inch: {1}", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0)
        {
            // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
            System.Console.WriteLine("Set resolution values to 96 dpi");
            frame.SetResolution(96.0, 96.0);

            System.Console.WriteLine("The horizontal resolution of frame {0}, pixels per inch: {1}", i, horizontalResolution);
            System.Console.WriteLine("The vertical resolution, of frame {0}, pixels per inch: {1}", i, verticalResolution);
        }

        ++i;
    }
}
```

### 另请参见

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


