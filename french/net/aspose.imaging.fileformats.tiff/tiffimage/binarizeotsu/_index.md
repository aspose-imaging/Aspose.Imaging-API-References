---
title: BinarizeOtsu
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Binarisation dune image avec seuillage Otsu
type: docs
weight: 230
url: /fr/net/aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/
---
## TiffImage.BinarizeOtsu method

Binarisation d'une image avec seuillage Otsu

```csharp
public override void BinarizeOtsu()
```

### Exemples

L'exemple suivant binarise une image TIFF avec un seuillage Otsu. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Binariser l'image avec le seuillage Otsu.
    tiffImage.BinarizeOtsu();
    tiffImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [TiffImage](../../tiffimage)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->