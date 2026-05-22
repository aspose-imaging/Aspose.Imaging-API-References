---
title: "DjvuImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage method. RotateFlip 方法提供多种灵活的图像操作选项，允许您对图像进行旋转、翻转或在活动帧上独立执行这两项操作。无论您是在编辑照片、创建图形还是增强数字艺术，此方法都能对图像的方向和构图提供精确控制，轻松高效地实现您的创意愿景。"
type: docs
weight: 300
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/rotateflip/
---
## DjvuImage.RotateFlip method

`RotateFlip` 方法为图像提供多样的操作选项，允许您对活动帧独立进行旋转、翻转或两者兼施。无论是编辑照片、创建图形还是提升数字艺术，此方法都能对图像的方向和构图提供精确控制，确保轻松高效地实现您的创意构想。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转类型。 |

## 示例

此示例加载一张 DJVU 图像，将其顺时针旋转 90 度，并可选择水平和（或）垂直翻转图像。

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
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### 另请参见

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


