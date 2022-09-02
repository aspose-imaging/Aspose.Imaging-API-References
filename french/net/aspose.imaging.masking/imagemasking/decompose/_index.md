---
title: Decompose
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Effectue lopération de décomposition en utilisant les options de masquage spécifiées
type: docs
weight: 30
url: /fr/net/aspose.imaging.masking/imagemasking/decompose/
---
## ImageMasking.Decompose method

Effectue l'opération de décomposition en utilisant les options de masquage spécifiées

```csharp
public MaskingResult Decompose(MaskingOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | MaskingOptions | Les options de masquage. |

### Return_Value

Résultat de l'opération de masquage en tant que tableau de fournisseurs d'images de segments.

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

Cet exemple montre comment décomposer une image raster en plusieurs images à l'aide du masquage d'image et d'un masque manuel. Le masquage d'image est une technique de traitement d'image utilisée pour séparer l'arrière-plan des objets d'image de premier plan.

```csharp
[C#]

string dir = "c:\\temp\\";

// Définit un masque manuel.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Chaque cluster (segment) sera stocké dans un fichier PNG séparé.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Définit le masque manuel.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Utiliser l'algorithme de clustering manuel.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // Toutes les formes composant un masque seront combinées en une seule. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // La couleur de fond sera orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // La zone de l'image source à laquelle le masquage sera appliqué.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

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

### Voir également

* class [MaskingResult](../../../aspose.imaging.masking.result/maskingresult)
* class [MaskingOptions](../../../aspose.imaging.masking.options/maskingoptions)
* class [ImageMasking](../../imagemasking)
* espace de noms [Aspose.Imaging.Masking](../../imagemasking)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
