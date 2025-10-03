---
title: TiffImage.RotateFlip
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Perform rotation flipping or a combination of both operations exclusively on the active frame. This method allows precise manipulation of individual frames within the image sequence enhancing flexibility in image editing and composition within your application
type: docs
weight: 380
url: /net/aspose.imaging.fileformats.tiff/tiffimage/rotateflip/
---
## TiffImage.RotateFlip method

Perform rotation, flipping, or a combination of both operations exclusively on the active frame. This method allows precise manipulation of individual frames within the image sequence, enhancing flexibility in image editing and composition within your application.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | The rotate flip type. |

## Examples

This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.

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
    using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### See Also

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


