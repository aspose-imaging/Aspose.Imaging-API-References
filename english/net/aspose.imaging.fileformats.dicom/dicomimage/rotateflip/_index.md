---
title: DicomImage.RotateFlip
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Easily manipulate the active frame by rotating flipping or performing both actions simultaneously with this straightforward method. Ideal for developers who need to dynamically adjust the orientation of specific frames within their image sequences ensuring optimal presentation and alignment
type: docs
weight: 290
url: /net/aspose.imaging.fileformats.dicom/dicomimage/rotateflip/
---
## DicomImage.RotateFlip method

Easily manipulate the active frame by rotating, flipping, or performing both actions simultaneously with this straightforward method. Ideal for developers who need to dynamically adjust the orientation of specific frames within their image sequences, ensuring optimal presentation and alignment.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | The rotate flip type. |

## Examples

This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.

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
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### See Also

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


