---
title: "PngImage.HorizontalResolution"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PngImage 属性。检索或修改图像的水平分辨率。此属性表示图像水平轴上每英寸的像素数。调整此分辨率可能会影响图像在打印或显示时的实际尺寸。"
type: docs
weight: 90
url: /zh/net/aspose.imaging.fileformats.png/pngimage/horizontalresolution/
---
## PngImage.HorizontalResolution property

检索或修改图像的水平分辨率。此属性表示图像水平轴上每英寸的像素数。调整该分辨率会影响图像在打印或显示时的实际尺寸。

```csharp
public override double HorizontalResolution { get; set; }
```

## 示例

以下示例展示了如何设置 PNG 图像的水平/垂直分辨率。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

    // 获取 PngImage 的水平和垂直分辨率。
    double horizontalResolution = pngImage.HorizontalResolution;
    double verticalResolution = pngImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.Console.WriteLine("Set resolution values to 96 dpi");
        pngImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", pngImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", pngImage.VerticalResolution);
    }
}
```

### 另请参见

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


