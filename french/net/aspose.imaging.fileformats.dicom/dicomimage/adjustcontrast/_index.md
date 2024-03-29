---
title: AdjustContrast
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Imageaspose.imaging/image contraste
type: docs
weight: 140
url: /fr/net/aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/
---
## DicomImage.AdjustContrast method

[`Image`](../../../aspose.imaging/image) contraste

```csharp
public override void AdjustContrast(float contrast)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| contrast | Single | Valeur de contraste (dans la plage [-100 ; 100]) |

### Exemples

L'exemple suivant effectue la correction du contraste d'une image DICOM.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Définit la valeur de contraste. Les valeurs de contraste acceptées sont dans la plage [-100f, 100f].
    dicomImage.AdjustContrast(50f);
    dicomImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [DicomImage](../../dicomimage)
* espace de noms [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
