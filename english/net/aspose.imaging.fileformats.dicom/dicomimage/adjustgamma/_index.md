---
title: DicomImage.AdjustGamma
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Enhance image quality and adjust it with gamma correction a powerful technique for finetuning visual appearance. Perfect for developers aiming to optimize image presentation adjust color balance and ensure consistent rendering across different devices and environments
type: docs
weight: 130
url: /net/aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

Enhance image quality and adjust it with gamma correction, a powerful technique for fine-tuning visual appearance. Perfect for developers aiming to optimize image presentation, adjust color balance, and ensure consistent rendering across different devices and environments.

```csharp
public override void AdjustGamma(float gamma)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gamma | Single | Gamma for red, green and blue channels coefficient |

## Examples

The following example performs gamma-correction of a DICOM image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Set gamma coefficient for red, green and blue channels.
    dicomImage.AdjustGamma(2.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

Achieve precise color adjustments by applying gamma correction independently to the red, green, and blue components of an image. This method ensures accurate color balance and optimal visual output, catering to developers seeking granular control over image rendering and color accuracy.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | Single | Gamma for red channel coefficient |
| gammaGreen | Single | Gamma for green channel coefficient |
| gammaBlue | Single | Gamma for blue channel coefficient |

## Examples

The following example performs gamma-correction of a DICOM image applying different coefficients for color components.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Set individual gamma coefficients for red, green and blue channels.
    dicomImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


