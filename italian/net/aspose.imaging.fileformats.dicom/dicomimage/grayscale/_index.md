---
title: Grayscale
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Trasformazione di unimmagine nella sua rappresentazione in scala di grigi
type: docs
weight: 230
url: /it/net/aspose.imaging.fileformats.dicom/dicomimage/grayscale/
---
## DicomImage.Grayscale method

Trasformazione di un'immagine nella sua rappresentazione in scala di grigi

```csharp
public override void Grayscale()
```

### Esempi

L'esempio seguente trasforma un'immagine DICOM colorata nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da sfumature di grigio e contengono solo informazioni sull'intensità.

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

### Guarda anche

* class [DicomImage](../../dicomimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
