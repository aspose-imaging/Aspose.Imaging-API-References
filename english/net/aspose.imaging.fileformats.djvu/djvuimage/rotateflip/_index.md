---
title: DjvuImage.RotateFlip
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. The RotateFlip method offers versatile manipulation options for your image allowing you to rotate flip or perform both operations on the active frame independently. Whether youre editing photos creating graphics or enhancing digital art this method provides precise control over the orientation and composition of your images ensuring they meet your creative vision with ease and efficiency
type: docs
weight: 300
url: /net/aspose.imaging.fileformats.djvu/djvuimage/rotateflip/
---
## DjvuImage.RotateFlip method

The `RotateFlip` method offers versatile manipulation options for your image, allowing you to rotate, flip, or perform both operations on the active frame independently. Whether you're editing photos, creating graphics, or enhancing digital art, this method provides precise control over the orientation and composition of your images, ensuring they meet your creative vision with ease and efficiency.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | The rotate flip type. |

## Examples

This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.

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
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### See Also

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


