---
title: AutoMaskingGraphCutOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de masquage automatique de GraphCut.
type: docs
weight: 10460
url: /fr/net/aspose.imaging.masking.options/automaskinggraphcutoptions/
---
## AutoMaskingGraphCutOptions class

Les options de masquage automatique de GraphCut.

```csharp
public class AutoMaskingGraphCutOptions : GraphCutMaskingOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [AutoMaskingGraphCutOptions](automaskinggraphcutoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Args](../../aspose.imaging.masking.options/maskingoptions/args) { get; set; } | Obtient ou définit les arguments de l'algorithme de segmentation. |
| [AssumedObjects](../../aspose.imaging.masking.options/automaskinggraphcutoptions/assumedobjects) { get; set; } | Obtient ou définit les objets supposés. |
| [BackgroundReplacementColor](../../aspose.imaging.masking.options/maskingoptions/backgroundreplacementcolor) { get; set; } | Obtient ou définit la couleur de remplacement de l'arrière-plan. |
| [CalculateDefaultStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/calculatedefaultstrokes) { get; set; } | Obtient ou définit une valeur indiquant si les traits par défaut doivent être calculés. |
| [Decompose](../../aspose.imaging.masking.options/maskingoptions/decompose) { get; set; } | Obtient ou définit une valeur indiquant si inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan. |
| [DefaultBackgroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultbackgroundstrokes) { get; } | Obtient les traits d'arrière-plan par défaut. |
| [DefaultForegroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultforegroundstrokes) { get; } | Obtient les traits de premier plan par défaut pré-calculés. |
| [DefaultObjectsRectangles](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultobjectsrectangles) { get; } | Obtient les rectangles d'objets par défaut. |
| [ExportOptions](../../aspose.imaging.masking.options/maskingoptions/exportoptions) { get; set; } | Obtient ou définit les options d'exportation d'image. |
| [FeatheringRadius](../../aspose.imaging.masking.options/graphcutmaskingoptions/featheringradius) { get; set; } | Obtient ou définit le rayon de contour progressif. |
| [MaskingArea](../../aspose.imaging.masking.options/maskingoptions/maskingarea) { get; set; } | Obtient ou définit la zone de masquage. |
| [Method](../../aspose.imaging.masking.options/maskingoptions/method) { get; set; } | Obtient ou définit la méthode de segmentation. |
| [PrecalculationProgressEventHandler](../../aspose.imaging.masking.options/automaskinggraphcutoptions/precalculationprogresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression du processus de précalcul des points par défaut. |

### Exemples

Enregistrement du résultat du masquage d'image avec un contour progressif basé sur la taille de l'image. Le masquage d'image est effectué à l'aide de traits par défaut calculés automatiquement. La propriété Args de AutoMaskingGraphCutOptions peut être omise car les traits par défaut y sont placés à la fin.

```csharp
[C#]

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
                                                    CalculateDefaultStrokes = true,
                                                    FeatheringRadius = (Math.Max(image.Width, image.Height) / 500) + 1,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent
    };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Enregistrement du résultat du masquage d'image avec un contour progressif basé sur la taille de l'image. Le masquage d'image est effectué à l'aide de traits par défaut calculés automatiquement. De plus, les données des deux objets supposés sont également spécifiées dans la propriété AssumedObjects de AutoMaskingGraphCutOptions.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
                                                    AssumedObjects = assumedObjects,
                                                    CalculateDefaultStrokes = true,
                                                    FeatheringRadius = (Math.Max(image.Width, image.Height) / 500) + 1,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent
    };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Enregistrement du résultat du masquage d'image avec un contour progressif basé sur la taille de l'image et réutilisation des options de masquage pour la nouvelle itération de masquage. Le masquage d'image est effectué à l'aide de traits par défaut calculés automatiquement. De plus, les données des deux objets supposés sont également spécifiées dans la propriété AssumedObjects de AutoMaskingGraphCutOptions. Après avoir obtenu le résultat de masquage initial, les traits d'arrière-plan/avant-plan appliqués sont modifiés et une autre itération de masquage est effectuée.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// À ce stade, les traits de premier plan / arrière-plan appliqués peuvent être analysés et basés sur eux 
// les traits de premier plan/arrière-plan peuvent être fournis manuellement.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // En réutilisant AutoMaskingGraphCutOptions, il n'est pas nécessaire d'effectuer les calculs de traits par défaut une deuxième fois.
    options.CalculateDefaultStrokes = false;
    // Lorsque les traits par défaut et les ObjectsPoints dans la propriété Args d'AutoMaskingArgs sont fournis, les tableaux de points sont finalement combinés.
    // Le premier tableau ObjectsPoints est considéré comme un tableau de points d'arrière-plan et 
    // le deuxième tableau ObjectsPoints est considéré comme un tableau de points de premier plan.
    // Lorsque DefaultObjectsRectangles et ObjectsRectangles dans la propriété Args de AutoMaskingArgs sont fournis, 
    // seul le tableau de Args est utilisé.
    options.Args = new AutoMaskingArgs()
                        {
                            ObjectsPoints = new Point[][]
                                                {
                                                    new Point[] { new Point(100, 100), new Point(150, 100) }, 
                                                    new Point[] { new Point(500, 200) }, 
                                                },
                            ObjectsRectangles = new Rectangle[]
                                                    {
                                                        new Rectangle(100, 100, 300, 300), 
                                                    }
                        };
    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Enregistrement du résultat du masquage d'image avec un contour progressif en fonction de la taille de l'image, modification des traits par défaut obtenus et utilisation de celui-ci pour la nouvelle itération de masquage. Le masquage d'image est effectué à l'aide de traits par défaut calculés automatiquement. De plus, les données des deux objets supposés sont également spécifiées dans la propriété AssumedObjects de AutoMaskingGraphCutOptions. Après avoir obtenu le résultat de masquage initial, les traits d'arrière-plan/avant-plan appliqués sont modifiés et une autre itération de masquage est effectuée à l'aide de la nouvelle instance GraphCutMaskingOptions.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// À ce stade, les traits de premier plan / arrière-plan appliqués peuvent être analysés et basés sur eux 
// les traits de premier plan/arrière-plan peuvent être fournis manuellement.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions()
                                                    {
                                                        FeatheringRadius = 3,
                                                        Method = SegmentationMethod.GraphCut,
                                                        Decompose = false,
                                                        ExportOptions = new PngOptions()
                                                                            {
                                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                                Source = new FileCreateSource("tempFile")
                                                                            },
                                                        BackgroundReplacementColor = Color.Transparent,
                                                        Args = new AutoMaskingArgs()
                                                                {
                                                                    ObjectsPoints = new Point[][]
                                                                                        {
                                                                                            appliedBackgroundStrokes,
                                                                                            appliedForegroundStrokes
                                                                                        },
                                                                    ObjectsRectangles = appliedObjectRectangles
                                                                }
                                                    };
    results = new ImageMasking(image).Decompose(graphCutOptions);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir également

* class [GraphCutMaskingOptions](../graphcutmaskingoptions)
* espace de noms [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
