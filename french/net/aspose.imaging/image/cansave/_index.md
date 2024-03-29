---
title: CanSave
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Détermine si limage peut être enregistrée dans le format de fichier spécifié représenté par les options denregistrement transmises.
type: docs
weight: 170
url: /fr/net/aspose.imaging/image/cansave/
---
## Image.CanSave method

Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises.

```csharp
public bool CanSave(ImageOptionsBase options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | ImageOptionsBase | Les options de sauvegarde à utiliser. |

### Return_Value

`vrai` si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement passées ; Par ailleurs,`faux` .

### Exemples

Cet exemple montre comment déterminer si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
    saveOptions.Quality = 50;

    // Détermine si l'image peut être enregistrée au format Jpeg
    bool canSave = image.CanSave(saveOptions);
}
```

### Voir également

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
