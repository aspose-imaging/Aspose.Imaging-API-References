---
title: "枚举 RotateFlipType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.RotateFlipType 枚举。指定图像旋转的角度以及用于翻转图像的轴。"
type: docs
weight: 11480
url: /zh/net/aspose.imaging/rotatefliptype/
---
## RotateFlipType enumeration

指定图像旋转的角度以及用于翻转图像的轴。

```csharp
public enum RotateFlipType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| RotateNoneFlipNone | `0` | 指定没有顺时针旋转，也没有翻转。 |
| Rotate90FlipNone | `1` | 指定 90 度顺时针旋转且不翻转。 |
| Rotate180FlipNone | `2` | 指定 180 度顺时针旋转且不翻转。 |
| Rotate270FlipNone | `3` | 指定 270 度顺时针旋转且不翻转。 |
| RotateNoneFlipX | `4` | 指定没有顺时针旋转，随后进行水平翻转。 |
| Rotate90FlipX | `5` | 指定 90 度顺时针旋转，随后进行水平翻转。 |
| Rotate180FlipX | `6` | 指定 180 度顺时针旋转，随后进行水平翻转。 |
| Rotate270FlipX | `7` | 指定 270 度顺时针旋转，随后进行水平翻转。 |
| RotateNoneFlipY | `8` | 指定没有顺时针旋转，随后进行垂直翻转。 |
| Rotate90FlipY | `9` | 指定 90 度顺时针旋转，随后进行垂直翻转。 |
| Rotate180FlipY | `10` | 指定 180 度顺时针旋转，随后进行垂直翻转。 |
| Rotate270FlipY | `11` | 指定 270 度顺时针旋转，随后进行垂直翻转。 |
| RotateNoneFlipXY | `12` | 指定没有顺时针旋转，随后进行水平和垂直翻转。 |
| Rotate90FlipXY | `13` | 指定 90 度顺时针旋转，随后进行水平和垂直翻转。 |
| Rotate180FlipXY | `14` | 指定 180 度顺时针旋转，随后进行水平和垂直翻转。 |
| Rotate270FlipXY | `15` | 指定 270 度顺时针旋转，随后进行水平和垂直翻转。 |

## 示例

此示例加载图像，将其顺时针旋转90度，并可选地水平和（或）垂直翻转图像。

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
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


