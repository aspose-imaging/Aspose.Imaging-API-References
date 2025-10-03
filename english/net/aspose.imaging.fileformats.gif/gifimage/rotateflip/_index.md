---
title: GifImage.RotateFlip
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Perform rotation flipping or both on the active frame exclusively. This operation applies transformations solely to the currently active frame of the image preserving the integrity of other frames in the sequence
type: docs
weight: 400
url: /net/aspose.imaging.fileformats.gif/gifimage/rotateflip/
---
## GifImage.RotateFlip method

Perform rotation, flipping, or both on the active frame exclusively. This operation applies transformations solely to the currently active frame of the image, preserving the integrity of other frames in the sequence.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | The rotate flip type. |

## Examples

This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.

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
    using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### See Also

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


