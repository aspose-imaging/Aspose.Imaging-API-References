---
title: OdgImage.RotateFlip
second_title: Aspose.Imaging for .NET API Reference
description: OdgImage method. This versatile method apply various transformations to images including rotation and flipping to achieve desired orientations and visual effects. With intuitive parameters you can specify the degree of rotation and the type of flipping horizontal vertical or both to precisely manipulate the image as needed
type: docs
weight: 60
url: /net/aspose.imaging.fileformats.opendocument/odgimage/rotateflip/
---
## OdgImage.RotateFlip method

This versatile method apply various transformations to images, including rotation and flipping, to achieve desired orientations and visual effects. With intuitive parameters, you can specify the degree of rotation and the type of flipping (horizontal, vertical, or both) to precisely manipulate the image as needed.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Type of the rotate flip. |

## Examples

This example loads a ODG image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.

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
    using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### See Also

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [OdgImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage/)
* assembly [Aspose.Imaging](../../../)


