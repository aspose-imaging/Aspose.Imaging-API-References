---
title: Rotate
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Faire pivoter limage autour du centre.
type: docs
weight: 370
url: /fr/net/aspose.imaging.fileformats.tiff/tiffimage/rotate/
---
## TiffImage.Rotate method

Faire pivoter l'image autour du centre.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| angle | Single | L'angle de rotation en degrés. Les valeurs positives tourneront dans le sens des aiguilles d'une montre. |
| resizeProportionally | Boolean | si réglé sur`vrai` la taille de votre image sera modifiée en fonction des projections du rectangle pivoté (points d'angle) dans un autre cas qui laisse les dimensions intactes et seul le contenu de l'image interne est pivoté. |
| backgroundColor | Color | Couleur du fond. |

### Exemples

L'exemple suivant montre comment faire pivoter une image TIFF autour du centre de 45 degrés dans le sens des aiguilles d'une montre.

```csharp
[C#]

string dir = "c:\\temp\\";
Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Crée une source de fichier permanente et non temporaire.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "rotated.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Remplir le cadre actif avec le pinceau dégradé linéaire.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Fait pivoter l'image autour du centre de 45 degrés dans le sens des aiguilles d'une montre. 
    // La taille de l'image a changé en fonction du rectangle pivoté (points d'angle).
    tiffImage.Rotate(45f, true, Aspose.Imaging.Color.Black);
    tiffImage.Save();

    // Fait pivoter l'image autour du centre de 45 degrés dans le sens des aiguilles d'une montre.
    // Laissez les dimensions de l'image inchangées et seul le contenu interne de l'image est pivoté.
    tiffImage.Rotate(45f, false, Aspose.Imaging.Color.Gray);
    tiffImage.Save(dir + "rotated.preservesize.tif");
}
```

### Voir également

* struct [Color](../../../aspose.imaging/color)
* class [TiffImage](../../tiffimage)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->