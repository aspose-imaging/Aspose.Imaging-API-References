---
title: DicomImage.AdjustBrightness
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Enhance image luminance with the adjustment of brightness a parameterized method that allows developers to finely tune the luminosity of images. This userfriendly function empowers developers to seamlessly manipulate image brightness offering flexibility and control over visual aesthetics
type: docs
weight: 110
url: /net/aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness/
---
## DicomImage.AdjustBrightness method

Enhance image luminance with the adjustment of *brightness*, a parameterized method that allows developers to finely tune the luminosity of images. This user-friendly function empowers developers to seamlessly manipulate image brightness, offering flexibility and control over visual aesthetics.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightness | Int32 | Brightness value. |

## Examples

The following example performs brightness correction of a DICOM image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    dicomImage.AdjustBrightness(50);
    dicomImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


