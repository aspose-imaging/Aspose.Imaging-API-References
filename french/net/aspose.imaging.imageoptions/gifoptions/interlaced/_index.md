---
title: Interlaced
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Vrai si limage doit être entrelacée.
type: docs
weight: 80
url: /fr/net/aspose.imaging.imageoptions/gifoptions/interlaced/
---
## GifOptions.Interlaced property

Vrai si l'image doit être entrelacée.

```csharp
public bool Interlaced { get; set; }
```

### Exemples

Cet exemple montre comment enregistrer une image BMP au format GIF à l'aide de diverses options.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(1000, 1000))
{
    // Remplir toute l'image avec le dégradé bleu-jaune.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(bmpImage);
    graphics.FillRectangle(gradientBrush, bmpImage.Bounds);

    Aspose.Imaging.ImageOptions.GifOptions saveOptions = new Aspose.Imaging.ImageOptions.GifOptions();

    // Le nombre de bits requis pour stocker une couleur, moins 1.
    saveOptions.ColorResolution = 7;

    // La correction de la palette signifie que chaque fois que l'image est exportée au format GIF, les couleurs de l'image source seront analysées
    // afin de construire la meilleure palette correspondante (au cas où l'image Palette n'existe pas ou n'est pas spécifiée dans les options)
    saveOptions.DoPaletteCorrection = true;

    // Charge une image GIF de manière progressive.
    // Un GIF entrelacé n'affiche pas ses scanlines linéairement de haut en bas, mais le réorganise à la place
    // afin que le contenu du GIF devienne clair avant même qu'il ne finisse de se charger.
    saveOptions.Interlaced = true;

    // Enregistrer en tant que GIF sans perte.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossless GIF: {0} bytes.", stream.Length);
    }

    // Définit la différence de pixels maximale autorisée. S'il est supérieur à zéro, une compression avec perte sera utilisée.
    // La valeur recommandée pour une compression avec perte optimale est de 80. 30 est une compression très légère, 200 est lourde.
    saveOptions.MaxDiff = 80;

    // Enregistrer en tant que GIF avec perte.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.lossy.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossy GIF: {0} bytes.", stream.Length);
    }
}

//La sortie peut ressembler à ceci :
// La taille du GIF sans perte : 212 816 octets.
// La taille du GIF avec perte : 89 726 octets.
```

### Voir également

* class [GifOptions](../../gifoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../gifoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
