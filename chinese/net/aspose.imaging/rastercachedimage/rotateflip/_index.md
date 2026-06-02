---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedImage 方法。旋转、翻转或旋转并翻转图像"
type: docs
weight: 200
url: /zh/net/aspose.imaging/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

旋转、翻转或同时旋转和翻转图像。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转类型。 |

## 示例

此示例加载一个栅格缓存图像，将其顺时针旋转90度，并可选地水平和（或）垂直翻转图像。

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

### 另请参见

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


