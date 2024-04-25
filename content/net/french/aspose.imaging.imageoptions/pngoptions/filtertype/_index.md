---
title: FilterType
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit le type de filtre utilisé lors du processus denregistrement du fichier png.
type: docs
weight: 50
url: /fr/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

Obtient ou définit le type de filtre utilisé lors du processus d'enregistrement du fichier png.

```csharp
public PngFilterType FilterType { get; set; }
```

### Exemples

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

L'exemple suivant montre comment différents types de filtres affectent la taille de l'image PNG de sortie.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Définir un type de filtre
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//La sortie peut ressembler à ceci :
//Le type de filtre est Aucun, la taille de l'image de sortie est de 116845 octets.
//Le type de filtre est Up, la taille de l'image de sortie est de 86360 octets.
//Le type de filtre est Sub, la taille de l'image de sortie est de 94907 octets.
//Le type de filtre est Paeth, la taille de l'image de sortie est de 86403 octets.
//Le type de filtre est Avg, la taille de l'image de sortie est de 89956 octets.
//Le type de filtre est adaptatif, la taille de l'image de sortie est de 97248 octets.
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

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../pngoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
