---
title: ResolutionSettings
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit les paramètres de résolution.
type: docs
weight: 60
url: /fr/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

Obtient ou définit les paramètres de résolution.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

### Exemples

L'exemple suivant charge une image BMP et l'enregistre dans BMP à l'aide de diverses options d'enregistrement.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Créer des BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
    saveOptions.BitsPerPixel = 8;

    // Définit la palette de couleurs 8 bits la plus proche qui couvre le nombre maximal de pixels de l'image, de sorte qu'une image palettisée
    // est presque impossible à distinguer visuellement d'un non palettisé.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Enregistrer sans compression.
    // Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Définissez la résolution horizontale et verticale sur 96 dpi.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

L'exemple suivant charge une image BMP et l'enregistre au format JPEG à l'aide de diverses options d'enregistrement.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image BMP à partir d'un fichier.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Effectue un traitement d'image.

    // Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Le nombre de bits par canal est de 8.
    // Lorsqu'une palette est utilisée, l'index de couleur est stocké dans les données de l'image au lieu de la couleur elle-même.
    saveOptions.BitsPerChannel = 8;

    // Définit le type de compression progressive.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Définit la qualité de l'image. C'est une valeur comprise entre 1 et 100.
    saveOptions.Quality = 100;

    // Définissez la résolution horizontale/verticale sur 96 points par pouce.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Si l'image source est colorée, elle sera convertie en niveaux de gris.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Utilisez une palette pour réduire la taille de sortie.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

L'exemple suivant crée une image BMP palettisée en niveaux de gris, puis l'enregistre dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Enregistrer dans un fichier
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
createOptions.BitsPerPixel = 8;

// Définit la palette de couleurs standard en niveaux de gris 8 bits qui couvre toutes les couleurs en niveaux de gris.
// Si l'image traitée ne contient que des couleurs en niveaux de gris, alors sa version palettisée
// est visuellement impossible à distinguer d'un non palettisé.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Enregistrer sans compression.
// Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Définissez la résolution horizontale et verticale sur 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Crée une image BMP de 100 x 100 px et l'enregistre dans un fichier.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Remplit l'image avec un dégradé de gris
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

L'exemple suivant montre comment créer une image JPEG de la taille spécifiée avec les paramètres spécifiés.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image JPEG de 100x100 px.
// Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Le nombre de bits par canal est de 8, 8, 8 pour les composants Y, Cr, Cb en conséquence.
createOptions.BitsPerChannel = 8;

// Définit le type de compression progressive.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Définit la qualité de l'image. C'est une valeur comprise entre 1 et 100.
createOptions.Quality = 100;

// Définissez la résolution horizontale/verticale sur 96 points par pouce.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Il s'agit d'une option standard pour les images JPEG.
// Deux composants chroma (Cb et Cr) peuvent être réduits en bande passante, sous-échantillonnés, compressés.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Remplit l'image avec un dégradé de gris
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Enregistrer dans un fichier.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Voir également

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* espace de noms [Aspose.Imaging](../../imageoptionsbase)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
