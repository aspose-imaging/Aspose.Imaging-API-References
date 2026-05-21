---
title: "AutoMaskingArgs"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente les arguments qui sont spécifiés pour les méthodes de masquage automatisées"
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Représente les arguments qui sont spécifiés pour les méthodes de masquage automatisées
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | Obtient le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Définit le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan). |
| [getObjectsRectangles()](#getObjectsRectangles--) | Obtient les rectangles d'objets appartenant aux objets séparés (facultatif). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | Définit les rectangles d'objets appartenant aux objets séparés (facultatif). |
| [getObjectsPoints()](#getObjectsPoints--) | Obtient les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | Définit les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale. |
| [getOrphanedPoints()](#getOrphanedPoints--) | Obtient les points qui n'appartiennent plus à aucun objet (facultatif). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | Définit les points qui n'appartiennent plus à aucun objet (facultatif). |
| [getPrecision()](#getPrecision--) | Obtient la précision de la méthode de segmentation (facultatif). |
| [setPrecision(double value)](#setPrecision-double-) | Définit la précision de la méthode de segmentation (facultatif). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Obtient le nombre maximal d'itérations. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Définit le nombre maximal d'itérations. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
Cet exemple montre comment décomposer une image raster en plusieurs images en utilisant le masquage d'image et l'algorithme de segmentation K-means. Le masquage d'image est une technique de traitement d'image qui sert à séparer l'arrière-plan des objets d'image au premier plan.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Définissez le nombre de clusters (objets séparés). La valeur par défaut est 2, l'objet du premier plan et l'arrière-plan.
    args.setNumberOfObjects(3);

    // Définissez le nombre maximal d'itérations.
    args.setMaxIterationNumber(50);

    // Définissez la précision de la méthode de segmentation (facultatif).
    args.setPrecision(1);

    // Chaque cluster (segment) sera enregistré dans un fichier PNG séparé.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Utilisez le clustering K-means.
    // Le clustering K-means permet de diviser l'image en plusieurs clusters (segments) indépendants.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // La couleur d'arrière-plan sera orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Diviser l'image source en plusieurs clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Obtenez les images à partir du résultat du masquage et enregistrez-les au format PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            final IMaskingLayer resultsItem = maskingResults.get_Item(i);
            String outputFileName = String.format("Blue hills.Segment%s.png", resultsItem.getObjectNumber());
            Image resultImage = resultsItem.getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
Cet exemple montre comment spécifier des suggestions pour l'algorithme de masquage d'image afin d'améliorer la précision de la méthode de segmentation (clustering). Le masquage d'image est une technique de traitement d'image qui sert à séparer l'arrière-plan des objets d'image au premier plan.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Suggestion n° 1.
    // Analysez l'image visuellement et définissez la zone d'intérêt. Le résultat de la segmentation ne comprendra que les objets qui seront entièrement situés dans cette zone.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Suggestion n° 2.
    // Analyse l'image visuellement et définit les points qui appartiennent à des objets séparés.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Chaque cluster (segment) sera enregistré dans un fichier PNG séparé.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Utilisez le clustering GraphCut.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // La couleur d'arrière-plan sera orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Diviser l'image source en plusieurs clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtenez les images à partir du résultat du masquage et enregistrez-les au format PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: Using a segment mask to speed up the segmentation process

``` java
// Options d’exportation du masquage
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Utilisez le clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// La couleur d'arrière-plan sera transparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Réduire la taille de l'image pour accélérer le processus de segmentation
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Diviser l'image source en plusieurs clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Obtention du masque de premier plan
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Augmenter la taille du masque à celle de l'image originale
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Appliquer le masque à l'image originale pour obtenir un segment de premier plan
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Options d’exportation du masquage
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Utilisez le clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// La couleur d'arrière-plan sera orange.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Démarrage d'une session pour la première fois et enregistrement dans un fichier
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Reprise d'une session de masquage à partir d'un fichier
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analyse l'image visuellement et définit les points qui appartiennent à des objets séparés.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Transfert explicite des options d'exportation, car il n'est pas sérialisable
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Obtient le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan).

Valeur : le nombre d'objets.

**Returns:**
int - le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Définit le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan).

Valeur : le nombre d'objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Obtient les rectangles d'objets appartenant aux objets séparés (facultatif). Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur : les rectangles d'objets.

**Returns:**
com.aspose.imaging.Rectangle[] - les rectangles d'objets appartenant aux objets séparés (facultatif).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Définit les rectangles d'objets appartenant aux objets séparés (facultatif). Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur : les rectangles d'objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | les rectangles d'objets appartenant aux objets séparés (facultatif). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Obtient les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale. Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur : les points d'objets.

**Returns:**
com.aspose.imaging.Point[][] - les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Définit les points qui appartiennent à des objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent à NumberOfObjects objets de l'image initiale. Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur : les points d'objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | les points qui appartiennent à des objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent à NumberOfObjects objets de l'image initiale. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Obtient les points qui n'appartiennent plus à aucun objet (facultatif). Ce paramètre n'est utilisé que dans le cas d'une re‑segmentation.

Valeur : les points orphelins.

**Returns:**
com.aspose.imaging.Point[] - les points qui n'appartiennent plus à aucun objet (facultatif).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Définit les points qui n'appartiennent plus à aucun objet (facultatif). Ce paramètre n'est utilisé que dans le cas d'une re‑segmentation.

Valeur : les points orphelins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | les points qui n'appartiennent plus à aucun objet (facultatif). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Obtient la précision de la méthode de segmentation (facultatif).

Valeur : la précision de la méthode de segmentation (facultatif).

**Returns:**
double - la précision de la méthode de segmentation (facultatif).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Définit la précision de la méthode de segmentation (facultatif).

Valeur : la précision de la méthode de segmentation (facultatif).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | la précision de la méthode de segmentation (facultatif). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Obtient le nombre maximal d'itérations.

Valeur : le nombre maximal maximal d'itérations.

**Returns:**
int - le nombre maximal d'itérations.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Définit le nombre maximal d'itérations.

Valeur : le nombre maximal maximal d'itérations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre maximal d'itérations. |

