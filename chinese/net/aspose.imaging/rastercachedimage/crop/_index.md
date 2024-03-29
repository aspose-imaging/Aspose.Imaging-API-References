---
title: Crop
second_title: Aspose.Imaging for .NET API 参考
description: 裁剪图像
type: docs
weight: 90
url: /zh/net/aspose.imaging/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

裁剪图像。

```csharp
public override void Crop(Rectangle rectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 矩形。 |

### 例子

以下示例裁剪光栅缓存图像。裁剪区域通过 Aspose.Imaging.Rectangle 指定。

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // 裁剪图像。裁剪区域是图像的矩形中心区域。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.Crop(area);

    // 将裁剪后的图像保存为 PNG
    rasterImage.Save(dir + "sample.Crop.png");
}
```

### 也可以看看

* struct [Rectangle](../../rectangle)
* class [RasterCachedImage](../../rastercachedimage)
* 命名空间 [Aspose.Imaging](../../rastercachedimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
