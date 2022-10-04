---
title: BinarizeFixed
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Binarisation dune image avec seuil prédéfini
type: docs
weight: 220
url: /fr/net/aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/
---
## TiffImage.BinarizeFixed method

Binarisation d'une image avec seuil prédéfini

```csharp
public override void BinarizeFixed(byte threshold)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| threshold | Byte | Valeur de seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, 0 sinon. |

### Exemples

L'exemple suivant binarise une image TIFF avec le seuil prédéfini. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Binarise l'image avec une valeur seuil de 127.
    // Si une valeur de gris correspondante d'un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, 0 sinon.
    tiffImage.BinarizeFixed(127);
    tiffImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [TiffImage](../../tiffimage)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->