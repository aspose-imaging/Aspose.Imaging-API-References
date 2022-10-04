---
title: CreateFrameFrom
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Crée le cadre à partir de spécifiétiffFrame en utilisant le spécifiéoptions . Les données de pixel sont conservées mais converties au format souhaité.
type: docs
weight: 30
url: /fr/net/aspose.imaging.fileformats.tiff/tiffframe/createframefrom/
---
## TiffFrame.CreateFrameFrom method

Crée le cadre à partir de spécifié*tiffFrame* en utilisant le spécifié*options* . Les données de pixel sont conservées mais converties au format souhaité.

```csharp
public static TiffFrame CreateFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| tiffFrame | TiffFrame | Le cadre tiff à partir duquel créer. |
| options | TiffOptions | Les nouvelles options à utiliser. |

### Return_Value

Le cadre nouvellement créé.

### Exemples

L'exemple suivant montre comment créer une copie en niveaux de gris d'un cadre existant et l'ajouter à une image TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Crée une source de fichier permanente et non temporaire.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
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

    // Remplir le cadre actif avec un pinceau dégradé linéaire.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Options de niveaux de gris
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Crée une copie en niveaux de gris du cadre actif.
    // Les données de pixel sont conservées mais converties au format souhaité.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Ajoute le cadre nouvellement créé à l'image TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Voir également

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->