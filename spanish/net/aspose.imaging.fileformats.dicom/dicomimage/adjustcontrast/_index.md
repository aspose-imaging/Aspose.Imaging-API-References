---
title: AdjustContrast
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Imageaspose.imaging/image contrastando
type: docs
weight: 140
url: /es/net/aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/
---
## DicomImage.AdjustContrast method

[`Image`](../../../aspose.imaging/image) contrastando

```csharp
public override void AdjustContrast(float contrast)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| contrast | Single | Valor de contraste (en el rango [-100; 100]) |

### Ejemplos

El siguiente ejemplo realiza la corrección de contraste de una imagen DICOM.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Establecer el valor de contraste. Los valores de contraste aceptados están en el rango [-100f, 100f].
    dicomImage.AdjustContrast(50f);
    dicomImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [DicomImage](../../dicomimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->