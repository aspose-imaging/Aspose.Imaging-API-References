---
title: AutoMaskingArgs
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente les arguments spécifiés pour les méthodes de masquage automatisées
type: docs
weight: 10450
url: /fr/aspose.imaging.masking.options/automaskingargs/
---
## AutoMaskingArgs class

Représente les arguments spécifiés pour les méthodes de masquage automatisées

```csharp
public class AutoMaskingArgs : IMaskingArgs
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [AutoMaskingArgs](automaskingargs)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [MaxIterationNumber](../../aspose.imaging.masking.options/automaskingargs/maxiterationnumber) { get; set; } | Obtient ou définit le nombre maximal d'itérations. |
| [NumberOfObjects](../../aspose.imaging.masking.options/automaskingargs/numberofobjects) { get; set; } | Obtient ou définit le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan). |
| [ObjectsPoints](../../aspose.imaging.masking.options/automaskingargs/objectspoints) { get; set; } | Obtient ou définit les points qui appartiennent à des objets séparés (facultatif) Coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale. Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation. |
| [ObjectsRectangles](../../aspose.imaging.masking.options/automaskingargs/objectsrectangles) { get; set; } | Obtient ou définit les objets rectangles qui appartiennent à des objets séparés (facultatif). Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation. |
| [OrphanedPoints](../../aspose.imaging.masking.options/automaskingargs/orphanedpoints) { get; set; } | Obtient ou définit les points qui n'appartiennent plus à aucun objet (facultatif). Ce paramètre est utilisé uniquement en cas de re-segmentation. |
| [Precision](../../aspose.imaging.masking.options/automaskingargs/precision) { get; set; } | Obtient ou définit la précision de la méthode de segmentation (facultatif). |

### Exemples

Cet exemple montre comment décomposer une image raster en plusieurs images à l'aide du masquage d'image et de l'algorithme de segmentation K-means. Le masquage d'image est une technique de traitement d'image utilisée pour séparer l'arrière-plan des objets d'image de premier plan.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Définit le nombre de clusters (objets séparés). La valeur par défaut est 2, l'objet de premier plan et l'arrière-plan.
    args.NumberOfObjects = 3;

    // Définit le nombre maximum d'itérations.
    args.MaxIterationNumber = 50;

    // Définit la précision de la méthode de segmentation (facultatif)
    args.Precision = 1;
        
    // Chaque cluster (segment) sera stocké dans un fichier PNG séparé.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Utilise le clustering K-means.
    // Le clustering K-means permet de scinder l'image en plusieurs clusters (segments) indépendants.
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // La couleur de fond sera orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Crée une instance de la classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divise l'image source en plusieurs clusters (segments).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Obtenez des images à partir du résultat de masquage et enregistrez-les au format PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

Utilisation d'un masque de segment pour accélérer le processus de segmentation

```csharp
[C#]

// Options d'exportation de masquage
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Utilise le clustering GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// La couleur de fond sera transparente.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Réduction de la taille de l'image pour accélérer le processus de segmentation
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Crée une instance de la classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divise l'image source en plusieurs clusters (segments).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Obtenir le masque de premier plan
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Augmente la taille du masque à la taille de l'image d'origine
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Application du masque à l'image d'origine pour obtenir un segment de premier plan
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

Cet exemple montre comment spécifier des suggestions pour l'algorithme de masquage d'image afin d'améliorer la précision de la méthode de segmentation (clustering). Le masquage d'image est une technique de traitement d'image utilisée pour séparer l'arrière-plan des objets d'image de premier plan.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Suggestion #1.
    // Analyse visuellement l'image et définit la zone d'intérêt. Le résultat de la segmentation n'inclura que les objets qui seront entièrement situés dans cette zone.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // Suggestion #2.
    // Analyse visuellement l'image et définit les points qui appartiennent à des objets séparés.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // Chaque cluster (segment) sera stocké dans un fichier PNG séparé.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // Utilise le clustering GraphCut.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // La couleur de fond sera orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Crée une instance de la classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divise l'image source en plusieurs clusters (segments).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Obtenez des images à partir du résultat de masquage et enregistrez-les au format PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Gorilla.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

Enregistrement de la session de masquage dans un fichier pour les longues sessions, ainsi que pour la possibilité de reprendre la session dans un autre environnement.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Options d'exportation de masquage
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Utilise le clustering GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// La couleur de fond sera orange.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Démarrage d'une session pour la première fois et enregistrement dans un fichier
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crée une instance de la classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// Reprise d'une session de masquage depuis un fichier
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crée une instance de la classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Analyse visuellement l'image et définit les points qui appartiennent à des objets séparés.
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // Transfert explicite des options d'exportation, car il n'est pas sérialisable
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Voir également

* interface [IMaskingArgs](../imaskingargs)
* espace de noms [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
