---
title: Dither
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Effectue un tramage sur limage actuelle.
type: docs
weight: 250
url: /fr/net/aspose.imaging.fileformats.tiff/tiffimage/dither/
---
## TiffImage.Dither method

Effectue un tramage sur l'image actuelle.

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | La méthode de tramage. |
| bitsCount | Int32 | Les derniers bits comptent pour le tramage. |
| customPalette | IColorPalette | La palette personnalisée pour le tramage. |

### Exemples

L'exemple suivant charge une image TIFF et effectue un tramage de seuil et Floyd en utilisant différentes profondeurs de palette.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Effectue un tramage de seuil à l'aide d'une palette de couleurs 4 bits contenant 16 couleurs.
    // Plus il y a de bits spécifiés, plus la qualité et la taille de l'image de sortie sont élevées.
    // Notez que seules les palettes 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Effectue un tramage Floyd en utilisant une palette de couleurs 1 bit qui ne contient que 2 couleurs - noir et blanc.
    // Plus il y a de bits spécifiés, plus la qualité et la taille de l'image de sortie sont élevées.
    // Notez que seules les palettes 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [TiffImage](../../tiffimage)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->