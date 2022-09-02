---
title: Palette
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit la palette de couleurs.
type: docs
weight: 40
url: /fr/net/aspose.imaging/imageoptionsbase/palette/
---
## ImageOptionsBase.Palette property

Obtient ou définit la palette de couleurs.

```csharp
public virtual IColorPalette Palette { get; set; }
```

### Valeur de la propriété

La palette de couleurs.

### Exemples

L'exemple suivant montre comment compresser une image PNG, en utilisant la couleur indexée avec la palette la mieux adaptée

```csharp
[C#]

// Charge l'image png        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Utiliser le type de couleur indexé
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Utiliser la compression maximale
         CompressionLevel = 9,
      // Obtient la palette de couleurs 8 bits la plus proche qui couvre autant de pixels que possible, de sorte qu'une image palettisée
         // est presque impossible à distinguer visuellement d'un non palettisé.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // La taille du fichier de sortie doit être considérablement réduite
```

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

L'exemple suivant montre comment palettiser une image BMP pour réduire sa taille de sortie.

```csharp
[C#]

// Crée une image BMP 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Remplir toute l'image avec le pinceau dégradé linéaire.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Obtient la palette de couleurs 8 bits la plus proche qui couvre autant de pixels que possible, de sorte qu'une image palettisée
    // est presque impossible à distinguer visuellement d'un non palettisé.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // La palette 8 bits contient au plus 256 couleurs.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// La sortie ressemble à ceci :
// La taille de l'image palettisée est de 11078 octets.
// La taille de l'image non palettisée est de 40054 octets.
```

### Voir également

* interface [IColorPalette](../../icolorpalette)
* class [ImageOptionsBase](../../imageoptionsbase)
* espace de noms [Aspose.Imaging](../../imageoptionsbase)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
