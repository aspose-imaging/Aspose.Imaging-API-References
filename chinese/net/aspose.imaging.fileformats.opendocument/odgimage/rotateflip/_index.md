---
title: "OdgImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "OdgImage 方法。此多功能方法对图像应用各种变换，包括旋转和翻转，以实现所需的方向和视觉效果。通过直观的参数，您可以指定旋转角度和翻转类型（水平、垂直或两者），精确地按需操作图像。"
type: docs
weight: 60
url: /zh/net/aspose.imaging.fileformats.opendocument/odgimage/rotateflip/
---
## OdgImage.RotateFlip method

此多功能方法对图像应用各种变换，包括旋转和翻转，以实现所需的方向和视觉效果。通过直观的参数，您可以指定旋转角度和翻转类型（水平、垂直或两者），精确地按需操作图像。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转的类型。 |

## 示例

此示例加载 ODG 图像，将其顺时针旋转 90 度，并可选择水平和（或）垂直翻转图像。

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
    using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### 另请参见

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [OdgImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage/)
* assembly [Aspose.Imaging](../../../)


