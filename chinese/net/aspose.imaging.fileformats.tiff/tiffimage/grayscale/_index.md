---
title: Grayscale
second_title: Aspose.Imaging for .NET API 参考
description: 将图像转换为其灰度表示
type: docs
weight: 280
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/grayscale/
---
## TiffImage.Grayscale method

将图像转换为其灰度表示

```csharp
public override void Grayscale()
```

### 例子

以下示例将彩色 TIFF 图像转换为其灰度表示。灰度图像仅由灰度阴影组成，仅携带强度信息。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    tiffImage.Grayscale();
    tiffImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [TiffImage](../../tiffimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
