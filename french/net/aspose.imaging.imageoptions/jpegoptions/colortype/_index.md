---
title: ColorType
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit le type de couleur pour limage jpeg.
type: docs
weight: 40
url: /fr/net/aspose.imaging.imageoptions/jpegoptions/colortype/
---
## JpegOptions.ColorType property

Obtient ou définit le type de couleur pour l'image jpeg.

```csharp
public JpegCompressionColorMode ColorType { get; set; }
```

### Exemples

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

L'exemple suivant charge PNG et l'enregistre au format JPEG CMJN à l'aide d'un profil ICC personnalisé. Charge ensuite CMJN JPEG et l'enregistre au format PNG. La conversion des couleurs de RVB en CMJN et de CMJN en RVB est effectuée à l'aide de profils ICC personnalisés.

```csharp
[C#]

string dir = "c:\\temp\\";

// Chargez PNG et enregistrez-le en CMJN JPEG
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // Utiliser des profils ICC personnalisés
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// Charger le JPEG CMJN et l'enregistrer au format PNG
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // Utiliser des profils ICC personnalisés
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
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

* enum [JpegCompressionColorMode](../../../aspose.imaging.fileformats.jpeg/jpegcompressioncolormode)
* class [JpegOptions](../../jpegoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../jpegoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
