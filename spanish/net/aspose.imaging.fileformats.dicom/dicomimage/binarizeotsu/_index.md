---
title: BinarizeOtsu
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Binarización de una imagen con umbral Otsu
type: docs
weight: 180
url: /es/net/aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu/
---
## DicomImage.BinarizeOtsu method

Binarización de una imagen con umbral Otsu

```csharp
public override void BinarizeOtsu()
```

### Ejemplos

El siguiente ejemplo binariza una imagen DICOM con el umbral de Otsu. Las imágenes binarizadas contienen solo 2 colores: blanco y negro.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Binarizar la imagen con el umbral de Otsu.
    dicomImage.BinarizeOtsu();
    dicomImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [DicomImage](../../dicomimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
