---
title: DicomImage.AdjustContrast
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Enhance Image contrast with this userfriendly method which adjusts the disparity between light and dark areas. Improve visual clarity and definition effortlessly providing developers with intuitive control over image contrast for optimal rendering
type: docs
weight: 120
url: /net/aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/
---
## DicomImage.AdjustContrast method

Enhance [`Image`](../../../aspose.imaging/image/) contrast with this user-friendly method, which adjusts the disparity between light and dark areas. Improve visual clarity and definition effortlessly, providing developers with intuitive control over image contrast for optimal rendering.

```csharp
public override void AdjustContrast(float contrast)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contrast | Single | Contrast value (in range [-100; 100]) |

## Examples

The following example performs contrast correction of a DICOM image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    dicomImage.AdjustContrast(50f);
    dicomImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


