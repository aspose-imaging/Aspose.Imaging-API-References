---
title: BinarizeOtsu
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Binarisation dune image avec seuillage Otsu
type: docs
weight: 200
url: /fr/net/aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/
---
## DjvuImage.BinarizeOtsu method

Binarisation d'une image avec seuillage Otsu

```csharp
public override void BinarizeOtsu()
```

### Exemples

L'exemple suivant binarise une image DJVU avec un seuillage Otsu. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Binariser l'image avec le seuillage Otsu.
    djvuImage.BinarizeOtsu();
    djvuImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [DjvuImage](../../djvuimage)
* espace de noms [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->