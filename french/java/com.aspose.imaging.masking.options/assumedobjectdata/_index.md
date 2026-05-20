---
title: "AssumedObjectData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les données des objets supposés."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.masking.options/assumedobjectdata/
---
**Inheritance:**
java.lang.Object
```
public class AssumedObjectData
```

Les données de l'objet supposé. Inclut le type et la zone de l'objet.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AssumedObjectData()](#AssumedObjectData--) | Initialise une nouvelle instance de la classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(int type, Rectangle bounds)](#AssumedObjectData-int-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(String type, Rectangle bounds)](#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Obtient le type de l'objet. |
| [setType(int value)](#setType-int-) | Définit le type de l'objet. |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Définit les limites de l'objet. |

## Example: Saving image masking result with feathering based on image size.
Enregistrement du résultat du masquage d'image avec plume en fonction de la taille de l'image. Le masquage d'image est effectué en utilisant les traits par défaut auto-calculés. De plus, les données des deux objets supposés sont également spécifiées dans la propriété AssumedObjects de AutoMaskingGraphCutOptions.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// libérer les ressources
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Enregistrement du résultat du masquage d'image avec plume en fonction de la taille de l'image et réutilisation des options de masquage pour la nouvelle itération de masquage. Le masquage d'image est effectué en utilisant les traits par défaut auto-calculés. De plus, les données des deux objets supposés sont également spécifiées dans la propriété AssumedObjects de AutoMaskingGraphCutOptions. Après obtention du résultat de masquage initial, les traits d'arrière-plan/avant-plan appliqués sont modifiés et une autre itération de masquage est effectuée.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// À ce stade, les traits d'avant-plan/arrière-plan appliqués peuvent être analysés et, sur cette base, supplémentaires
// les traits d'avant-plan/arrière-plan peuvent être fournis manuellement.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// libérer les ressources
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // En réutilisant AutoMaskingGraphCutOptions, il n'est pas nécessaire d'effectuer le calcul des traits par défaut une seconde fois.
    options.setCalculateDefaultStrokes(false);
    // Lorsque les traits par défaut et ObjectsPoints dans la propriété Args de AutoMaskingArgs sont fournis, les tableaux de points sont finalement combinés.
    // Le premier tableau ObjectsPoints est considéré comme un tableau de points d'arrière-plan et
    // le deuxième tableau ObjectsPoints est considéré comme un tableau de points de premier plan.
    // Lorsque les DefaultObjectsRectangles et ObjectsRectangles dans la propriété Args de AutoMaskingArgs sont fournis,
    // seul le tableau provenant des Args est utilisé.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// libérer les ressources
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Enregistrement du résultat de masquage d'image avec flou en fonction de la taille de l'image, modification des traits par défaut obtenus et utilisation pour la nouvelle itération de masquage. Le masquage d'image est effectué en utilisant des traits par défaut calculés automatiquement. De plus, les données des deux objets supposés sont également spécifiées dans la propriété AssumedObjects de AutoMaskingGraphCutOptions. Après obtention du résultat de masquage initial, les traits d'arrière-plan/avant-plan appliqués sont modifiés et une autre itération de masquage est réalisée en utilisant une nouvelle instance de GraphCutMaskingOptions.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// À ce stade, les traits d'avant-plan/arrière-plan appliqués peuvent être analysés et, sur cette base, supplémentaires
// les traits d'avant-plan/arrière-plan peuvent être fournis manuellement.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// libérer les ressources
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// libérer les ressources
for (MaskingResult res : results)
{
    res.close();
}
```

### AssumedObjectData() {#AssumedObjectData--}
```
public AssumedObjectData()
```


Initialise une nouvelle instance de la classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

### AssumedObjectData(int type, Rectangle bounds) {#AssumedObjectData-int-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(int type, Rectangle bounds)
```


Initialise une nouvelle instance de la classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de l'objet. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'objet. |

### AssumedObjectData(String type, Rectangle bounds) {#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(String type, Rectangle bounds)
```


Initialise une nouvelle instance de la classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | java.lang.String | Le type de l'objet. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'objet. |

### getType() {#getType--}
```
public final int getType()
```


Obtient le type de l'objet.

**Returns:**
int - le type de l'objet.
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Définit le type de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le type de l'objet. |

### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtient les limites de l'objet.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the object's bounds.
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Définit les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | les limites de l'objet. |

