---
title: Create8BitGrayscale
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Crée la palette de niveaux de gris 8 bits.
type: docs
weight: 40
url: /fr/net/aspose.imaging/colorpalettehelper/create8bitgrayscale/
---
## ColorPaletteHelper.Create8BitGrayscale method

Crée la palette de niveaux de gris 8 bits.

```csharp
public static IColorPalette Create8BitGrayscale(bool minIsWhite)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| minIsWhite | Boolean | si réglé sur`vrai` la palette commence par la couleur blanche, sinon elle commence par la couleur noire. |

### Return_Value

La palette de niveaux de gris 8 bits.

### Exemples

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

### Voir également

* interface [IColorPalette](../../icolorpalette)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espace de noms [Aspose.Imaging](../../colorpalettehelper)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
