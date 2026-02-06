---
title: Enum RotateFlipType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.RotateFlipType enum. Specifies how much an image is rotated and the axis used to flip the image
type: docs
weight: 11470
url: /net/aspose.imaging/rotatefliptype/
---
## RotateFlipType enumeration

Specifies how much an image is rotated and the axis used to flip the image.

```csharp
public enum RotateFlipType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RotateNoneFlipNone | `0` | Specifies no clockwise rotation and no flipping. |
| Rotate90FlipNone | `1` | Specifies a 90-degree clockwise rotation without flipping. |
| Rotate180FlipNone | `2` | Specifies a 180-degree clockwise rotation without flipping. |
| Rotate270FlipNone | `3` | Specifies a 270-degree clockwise rotation without flipping. |
| RotateNoneFlipX | `4` | Specifies no clockwise rotation followed by a horizontal flip. |
| Rotate90FlipX | `5` | Specifies a 90-degree clockwise rotation followed by a horizontal flip. |
| Rotate180FlipX | `6` | Specifies a 180-degree clockwise rotation followed by a horizontal flip. |
| Rotate270FlipX | `7` | Specifies a 270-degree clockwise rotation followed by a horizontal flip. |
| RotateNoneFlipY | `8` | Specifies no clockwise rotation followed by a vertical flip. |
| Rotate90FlipY | `9` | Specifies a 90-degree clockwise rotation followed by a vertical flip. |
| Rotate180FlipY | `10` | Specifies a 180-degree clockwise rotation followed by a vertical flip. |
| Rotate270FlipY | `11` | Specifies a 270-degree clockwise rotation followed by a vertical flip. |
| RotateNoneFlipXY | `12` | Specifies no clockwise rotation followed by a horizontal and vertical flip. |
| Rotate90FlipXY | `13` | Specifies a 90-degree clockwise rotation followed by a horizontal and vertical flip. |
| Rotate180FlipXY | `14` | Specifies a 180-degree clockwise rotation followed by a horizontal and vertical flip. |
| Rotate270FlipXY | `15` | Specifies a 270-degree clockwise rotation followed by a horizontal and vertical flip. |

## Examples

This example loads an image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.

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
    // Rotate, flip and save to the output file.
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


