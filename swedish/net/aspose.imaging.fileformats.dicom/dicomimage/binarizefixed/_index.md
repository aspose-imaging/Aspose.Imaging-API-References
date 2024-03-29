---
title: BinarizeFixed
second_title: Aspose.Imaging för .NET API-referens
description: Binarisering av en bild med fördefinierad tröskel
type: docs
weight: 170
url: /sv/net/aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/
---
## DicomImage.BinarizeFixed method

Binarisering av en bild med fördefinierad tröskel

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | Byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskelvärdet kommer ett värde på 255 att tilldelas den, annars 0. |

### Exempel

Följande exempel binariserar en DICOM-bild med den fördefinierade tröskeln. Binariserade bilder innehåller endast 2 färger - svart och vitt.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Binarisera bilden med ett tröskelvärde på 127.
    // Om ett motsvarande grått värde för en pixel är större än 127 kommer ett värde på 255 att tilldelas den, annars 0.
    dicomImage.BinarizeFixed(127);
    dicomImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [DicomImage](../../dicomimage)
* namnutrymme [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
