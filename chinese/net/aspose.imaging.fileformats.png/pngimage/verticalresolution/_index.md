---
title: VerticalResolution
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置垂直分辨率
type: docs
weight: 140
url: /zh/net/aspose.imaging.fileformats.png/pngimage/verticalresolution/
---
## PngImage.VerticalResolution property

获取或设置垂直分辨率。

```csharp
public override double VerticalResolution { get; set; }
```

### 例子

以下示例显示如何设置 PNG 图像的水平/垂直分辨率。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

        // 获取 PngImage.
 的水平和垂直分辨率
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

### 也可以看看

* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->