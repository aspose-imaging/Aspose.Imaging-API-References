---
title: BinarizeFixed
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Binarización de una imagen con umbral predefinido
type: docs
weight: 170
url: /es/net/aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/
---
## DicomImage.BinarizeFixed method

Binarización de una imagen con umbral predefinido

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| threshold | Byte | Valor umbral. Si el valor de gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255, 0 de lo contrario. |

### Ejemplos

El siguiente ejemplo binariza una imagen DICOM con el umbral predefinido. Las imágenes binarizadas contienen solo 2 colores: blanco y negro.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Binarizar la imagen con un valor de umbral de 127.
    // Si el valor de gris correspondiente de un píxel es mayor que 127, se le asignará un valor de 255, 0 en caso contrario.
    dicomImage.BinarizeFixed(127);
    dicomImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [DicomImage](../../dicomimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
