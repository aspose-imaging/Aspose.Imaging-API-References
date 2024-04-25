---
title: Compression
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit la compression.
type: docs
weight: 90
url: /fr/aspose.imaging.imageoptions/tiffoptions/compression/
---
## TiffOptions.Compression property

Obtient ou définit la compression.

```csharp
public TiffCompressions Compression { get; set; }
```

### Valeur de la propriété

La compression.

### Exemples

Cet exemple montre comment créer une image TIFF à partir de zéro et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Définissez 8 bits pour chaque composant de couleur.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Définir l'ordre des octets Big Endian (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Définit la compression LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Définit le modèle de couleur RVB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tous les composants de couleur seront stockés dans un seul plan.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crée un cadre TIFF de 100x100 px.
// Notez que vous n'avez pas besoin de supprimer explicitement un cadre s'il est inclus dans TiffImage.
// Lorsque le conteneur est supprimé, tous les cadres seront supprimés automatiquement.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Remplir tout le cadre avec le dégradé bleu-jaune.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Crée une image TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

Cet exemple montre comment enregistrer une image raster au format TIFF à l'aide de diverses options.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Définissez 8 bits pour chaque composant de couleur.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Définir l'ordre des octets Big Endian (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Définit la compression LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Permet de réduire la taille des images à tons continus.
// Actuellement, ce champ n'est utilisé qu'avec l'encodage LZW car LZW est probablement le seul schéma d'encodage TIFF
// qui bénéficie de manière significative d'une étape de prédiction.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// Définit le modèle de couleur RVB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Pour YCbCr, vous pouvez utiliser l'un des choix suivants :
// Champ YCbCrSubSampling Facteurs d'échantillonnage JPEG
// ----------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(valeur par défaut) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tous les composants de couleur seront stockés dans un seul plan.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crée un cadre TIFF de 100x100 px.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Remplir toute l'image avec le dégradé bleu-jaune.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

Cet exemple montre comment créer une image TIFF avec 2 cadres et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Options pour la première image
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Définissez 8 bits pour chaque composant de couleur.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Définir l'ordre des octets Big Endian (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Définit la compression LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Définit le modèle de couleur RVB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tous les composants de couleur seront stockés dans un seul plan.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crée la première image TIFF de 100x100 px.
// Notez que vous n'avez pas à supprimer explicitement les cadres s'ils sont inclus dans TiffImage.
// Lorsque le conteneur est supprimé, tous les cadres seront supprimés automatiquement.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Remplir le premier cadre avec le dégradé bleu-jaune.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Options pour la première image
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Définir 1 bit par pixel pour une image N/B.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Définit l'ordre des octets Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Définit la compression CCITT Group 3 Fax.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Définit le modèle de couleur N/B où 0 est noir, 1 est blanc.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Crée la deuxième image TIFF de 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Remplir le deuxième cadre avec le dégradé bleu-jaune.
// Il sera automatiquement converti au format N/B en raison des paramètres correspondants du cadre.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Crée une image TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Voir également

* enum [TiffCompressions](../../../aspose.imaging.fileformats.tiff.enums/tiffcompressions)
* class [TiffOptions](../../tiffoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
