---
title: CompressionMethod
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit la méthode de compression psd.
type: docs
weight: 50
url: /fr/net/aspose.imaging.imageoptions/psdoptions/compressionmethod/
---
## PsdOptions.CompressionMethod property

Obtient ou définit la méthode de compression psd.

```csharp
public CompressionMethod CompressionMethod { get; set; }
```

### Valeur de la propriété

La méthode de compression.

### Exemples

Cet exemple illustre l'utilisation de l'API Aspsoe.Imaging pour .Net pour convertir des images au format PSD. Pour atteindre cet objectif, cet exemple charge une image existante, puis l'enregistre au format PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une instance de la classe d'image et l'initialise avec un fichier existant via le chemin du fichier
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Créer une instance de la classe PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // Définissez CompressionMethod sur RLE
    //Remarque : l'autre méthode de compression prise en charge est CompressionMethod.RAW [Pas de compression]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    // Définissez le ColorMode sur GrayScale
    //Remarque : les autres ColorModes pris en charge sont ColorModes.Bitmap et ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    // Enregistrez l'image sur le disque avec les paramètres PsdOptions fournis
    image.Save(dir + "output.psd", psdOptions);
}
```

Cet exemple montre comment enregistrer une image PNG au format PSD à l'aide de diverses options spécifiques à PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha))
{
    // Définit un dégradé bleu-transparent linéaire.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Remplir l'image PNG avec le dégradé bleu-transparent linéaire.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Les options suivantes seront utilisées pour enregistrer l'image PNG au format PSD.
    Aspose.Imaging.ImageOptions.PsdOptions saveOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // Le nombre de bits par canal
    saveOptions.ChannelBitsCount = 8;

    // Le nombre de canaux. Un canal pour chaque composante de couleur R, G, B, A
    saveOptions.ChannelsCount = 4;

    // Le mode couleur
    saveOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Rgb;

    // Pas de compression
    saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.Raw;

    // La version par défaut est 6
    saveOptions.Version = 6;            

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.psd"))
    {
        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RAW compression: {0}", stream.Length);
    }

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.RLE.psd"))
    {
        // La compression RLE permet de réduire la taille de l'image de sortie
        saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.RLE;

        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RLE compression: {0}", stream.Length);
    }

    // La sortie peut ressembler à ceci :
    // La taille de l'image PSD avec compression RAW : 40090
    // La taille de l'image PSD avec compression RLE : 16185
}
```

### Voir également

* enum [CompressionMethod](../../../aspose.imaging.fileformats.psd/compressionmethod)
* class [PsdOptions](../../psdoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../psdoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
