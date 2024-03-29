---
title: Grayscale
second_title: Aspose.Imaging för .NET API-referens
description: Transformation av en bild till dess gråskalerepresentation
type: docs
weight: 230
url: /sv/net/aspose.imaging.fileformats.dicom/dicomimage/grayscale/
---
## DicomImage.Grayscale method

Transformation av en bild till dess gråskalerepresentation

```csharp
public override void Grayscale()
```

### Exempel

Följande exempel omvandlar en färgad DICOM-bild till dess gråskalerepresentation. Gråskalebilder består uteslutande av gråtoner och innehåller endast intensitetsinformation.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    dicomImage.Grayscale();
    dicomImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [DicomImage](../../dicomimage)
* namnutrymme [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
