---
title: DefaultBackgroundStrokes
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient les traits darrière-plan par défaut.
type: docs
weight: 40
url: /fr/net/aspose.imaging.masking.options/automaskinggraphcutoptions/defaultbackgroundstrokes/
---
## AutoMaskingGraphCutOptions.DefaultBackgroundStrokes property

Obtient les traits d'arrière-plan par défaut.

```csharp
public Point[] DefaultBackgroundStrokes { get; }
```

### Exemples

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

* struct [Point](../../../aspose.imaging/point)
* class [AutoMaskingGraphCutOptions](../../automaskinggraphcutoptions)
* espace de noms [Aspose.Imaging.Masking.Options](../../automaskinggraphcutoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
