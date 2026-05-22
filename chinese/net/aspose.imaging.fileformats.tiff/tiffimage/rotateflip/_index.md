---
title: "TiffImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。对活动帧执行旋转、翻转或两者的组合操作。此方法允许对图像序列中的单个帧进行精确操作，提升在应用程序中的图像编辑和构图灵活性。"
type: docs
weight: 380
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/rotateflip/
---
## TiffImage.RotateFlip method

仅在活动帧上执行旋转、翻转或两者的组合操作。此方法可对图像序列中的单帧进行精确操作，提升应用程序中图像编辑和合成的灵活性。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转类型。 |

## 示例

此示例加载 TIFF 图像，将其顺时针旋转 90 度，并可选地水平和（或）垂直翻转图像。

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
    using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### 另请参见

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


