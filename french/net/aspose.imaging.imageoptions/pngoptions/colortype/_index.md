---
title: ColorType
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit le type de la couleur.
type: docs
weight: 30
url: /fr/net/aspose.imaging.imageoptions/pngoptions/colortype/
---
## PngOptions.ColorType property

Obtient ou définit le type de la couleur.

```csharp
public PngColorType ColorType { get; set; }
```

### Valeur de la propriété

Le type de couleur.

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

Cet exemple montre comment créer une image PNG avec les options spécifiées, la remplir avec un dégradé de couleurs linéaire et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Le nombre de bits par canal de couleur
createOptions.BitDepth = 8;

// Chaque pixel est un triplet (rouge, vert, bleu) suivi de la composante alpha.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Le niveau maximum de compression.
createOptions.CompressionLevel = 9;

// L'utilisation de filtres permet de compresser plus efficacement les images tonales continues.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Utiliser le chargement progressif
createOptions.Progressive = true;

// Crée une image PNG avec des paramètres personnalisés.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Remplit l'image avec un dégradé semi-transparent.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Enregistrer dans un fichier.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

L'exemple suivant montre comment enregistrer une image au format PNG à l'aide de diverses options.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image PNG de 100x100 px.
// Vous pouvez également charger une image de n'importe quel format pris en charge à partir d'un fichier ou d'un flux.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Remplir l'image avec le dégradé bleu-transparent.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Chargement progressif.
    saveOptions.Progressive = true;

    // Définissez la résolution horizontale et verticale sur 96 pixels par pouce.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Chaque pixel est un triplet (rouge, vert, bleu) suivi d'alpha.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Définit le niveau maximum de compression.
    saveOptions.CompressionLevel = 9;

    // C'est la meilleure compression, mais le temps d'exécution le plus lent.
    // Le filtrage adaptatif signifie que le processus d'enregistrement choisira le filtre le plus fiable pour chaque ligne de données.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // Le nombre de bits par canal.
    saveOptions.BitDepth = 8;

    // Enregistrer dans un fichier.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Voir également

* enum [PngColorType](../../../aspose.imaging.fileformats.png/pngcolortype)
* class [PngOptions](../../pngoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../pngoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
