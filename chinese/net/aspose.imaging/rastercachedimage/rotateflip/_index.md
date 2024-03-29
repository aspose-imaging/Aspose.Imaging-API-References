---
title: RotateFlip
second_title: Aspose.Imaging for .NET API 参考
description: 旋转翻转或旋转和翻转图像
type: docs
weight: 140
url: /zh/net/aspose.imaging/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

旋转、翻转或旋转和翻转图像。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转类型。 |

### 例子

此示例加载光栅缓存图像，将其顺时针旋转 90 度，并可选择水平和（或）垂直翻转图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // 旋转、翻转并保存到输出文件。
    using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

### 也可以看看

* enum [RotateFlipType](../../rotatefliptype)
* class [RasterCachedImage](../../rastercachedimage)
* 命名空间 [Aspose.Imaging](../../rastercachedimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
