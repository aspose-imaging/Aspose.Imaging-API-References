---
title: Image.RotateFlip
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Rotates flips or rotates and flips the image
type: docs
weight: 300
url: /net/aspose.imaging/image/rotateflip/
---
## Image.RotateFlip method

Rotates, flips, or rotates and flips the image.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Type of the rotate flip. |

## Examples

This example demonstrates the use of Rotate operation on an image. Example loads an existing image file from some disk location and performs the Rotate operaation on the image according to the value of Enum Aspose.Imaging.RotateFlipType

```csharp
[C#]

//Create an instance of image class and initialize it with an existing image file through File path
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    //Rotate the image at 180 degree about X axis
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    // save all changes.
    image.Save();
}
```

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

foreach (Aspose.Imaging.Image rotateFlipType in rotateFlipTypes)
{
    // Rotate, flip and save to the output file.
    using (Aspose.Imaging.Image image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### See Also

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


