---
title: "ContentAwareFillWatermarkOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options communes de l'algorithme de remplissage sensible au contenu."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class ContentAwareFillWatermarkOptions extends WatermarkOptions
```

Les options communes de l'algorithme de remplissage sensible au contenu.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ContentAwareFillWatermarkOptions(Point[] mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---) | Initialise une nouvelle instance de la classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
| [ContentAwareFillWatermarkOptions(GraphicsPath mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Initialise une nouvelle instance de la classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPatchSize()](#getPatchSize--) | Obtient la taille du patch (doit être impair). |
| [setPatchSize(byte value)](#setPatchSize-byte-) | Définit la taille du patch (doit être impair). |
| [getMaxPaintingAttempts()](#getMaxPaintingAttempts--) | Obtient le nombre maximal de tentatives de peinture. |
| [setMaxPaintingAttempts(int value)](#setMaxPaintingAttempts-int-) | Définit le nombre maximal de tentatives de peinture. |
| [getInterestArea()](#getInterestArea--) | Obtient la zone où prélever les patches. |
| [setInterestArea(Rectangle value)](#setInterestArea-com.aspose.imaging.Rectangle-) | Définit la zone où prélever les patches. |

## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### ContentAwareFillWatermarkOptions(Point[] mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---}
```
public ContentAwareFillWatermarkOptions(Point[] mask)
```


Initialise une nouvelle instance de la classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Le masque pour la zone inconnue. |

### ContentAwareFillWatermarkOptions(GraphicsPath mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public ContentAwareFillWatermarkOptions(GraphicsPath mask)
```


Initialise une nouvelle instance de la classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le masque pour la zone inconnue. |

### getPatchSize() {#getPatchSize--}
```
public final byte getPatchSize()
```


Obtient la taille du patch (doit être impair).

Valeur : la taille du patch.

**Returns:**
byte - la taille du patch (doit être impair).
### setPatchSize(byte value) {#setPatchSize-byte-}
```
public final void setPatchSize(byte value)
```


Définit la taille du patch (doit être impair).

Valeur : la taille du patch.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | la taille du patch (doit être impair). |

### getMaxPaintingAttempts() {#getMaxPaintingAttempts--}
```
public final int getMaxPaintingAttempts()
```


Obtient le nombre maximal de tentatives de peinture. L'algorithme choisira la meilleure variante.

Valeur: le nombre maximal de tentatives de peinture.

**Returns:**
int - le nombre maximal de tentatives de peinture.

**Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.**

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### setMaxPaintingAttempts(int value) {#setMaxPaintingAttempts-int-}
```
public final void setMaxPaintingAttempts(int value)
```


Définit le nombre maximal de tentatives de peinture. L'algorithme choisira la meilleure variante.

Valeur: le nombre maximal de tentatives de peinture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre maximal de tentatives de peinture. |


**Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.**

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### getInterestArea() {#getInterestArea--}
```
public final Rectangle getInterestArea()
```


Obtient la zone où prélever les patches.

Valeur: la zone d'intérêt pour extraire des patches.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the area to take patches.
### setInterestArea(Rectangle value) {#setInterestArea-com.aspose.imaging.Rectangle-}
```
public final void setInterestArea(Rectangle value)
```


Définit la zone où prélever les patches.

Valeur: la zone d'intérêt pour extraire des patches.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | la zone pour extraire des patches. |

