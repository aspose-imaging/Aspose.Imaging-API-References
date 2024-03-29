---
title: AdjustContrast
second_title: Aspose.Imaging for .NET API 参考
description: Imageaspose.imaging/image对比
type: docs
weight: 180
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast/
---
## TiffImage.AdjustContrast method

[`Image`](../../../aspose.imaging/image)对比

```csharp
public override void AdjustContrast(float contrast)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contrast | Single | 对比度值（范围 [-100; 100]） |

### 例子

以下示例执行 TIFF 图像的对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 设置对比度值。可接受的对比度值在 [-100f, 100f] 范围内。
    tiffImage.AdjustContrast(50f);
    tiffImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [TiffImage](../../tiffimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
