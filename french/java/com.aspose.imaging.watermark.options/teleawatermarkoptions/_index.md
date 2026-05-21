---
title: "TeleaWatermarkOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options communes de l'algorithme Telea."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

Les options communes de l'algorithme Telea.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | Initialise une nouvelle instance de la classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Initialise une nouvelle instance de la classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | Obtient la moitié de la taille du patch. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | Définit la moitié de la taille du patch. |

## Example: The example shows how to remove any object from the image using Graphics Path with Telea algorithm.

``` java
String imageFilePath = "ball.png";
String outputPath = "no-watermark.png";
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage) image;
    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    TeleaWatermarkOptions options = new TeleaWatermarkOptions(mask);

    try (RasterImage result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.save(outputPath);
    }
}

```

### TeleaWatermarkOptions(Point[] mask) {#TeleaWatermarkOptions-com.aspose.imaging.Point---}
```
public TeleaWatermarkOptions(Point[] mask)
```


Initialise une nouvelle instance de la classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Le masque pour la zone inconnue. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


Initialise une nouvelle instance de la classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le masque pour la zone inconnue. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


Obtient la moitié de la taille du patch.

Valeur : la taille du patch.

**Returns:**
int - la moitié de la taille du patch.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


Définit la moitié de la taille du patch.

Valeur : la taille du patch.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la moitié de la taille du patch. |

