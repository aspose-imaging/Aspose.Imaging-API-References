---
title: CacheData
second_title: Aspose.Imaging för .NET API-referens
description: Cachelagrar data privat.
type: docs
weight: 190
url: /sv/net/aspose.imaging.fileformats.dicom/dicomimage/cachedata/
---
## DicomImage.CacheData method

Cachelagrar data privat.

```csharp
public override void CacheData()
```

### Exempel

Följande exempel visar hur man cachelagrar alla sidor i en DICOM-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en bild från en DICOM-fil.
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Detta anrop cachar alla sidor så att ingen ytterligare dataladdning kommer att utföras från den underliggande dataströmmen.
    image.CacheData();

    // Eller så kan du cachelagra sidorna individuellt.
    foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage page in image.DicomPages)
    {
        page.CacheData();
    }
}
```

### Se även

* class [DicomImage](../../dicomimage)
* namnutrymme [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->