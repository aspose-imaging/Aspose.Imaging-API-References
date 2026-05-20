---
title: "ContentAwareFillWatermarkOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le comuni opzioni dell'algoritmo Content Aware Fill."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class ContentAwareFillWatermarkOptions extends WatermarkOptions
```

Le comuni opzioni dell'algoritmo Content Aware Fill.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ContentAwareFillWatermarkOptions(Point[] mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---) | Inizializza una nuova istanza della classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
| [ContentAwareFillWatermarkOptions(GraphicsPath mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Inizializza una nuova istanza della classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPatchSize()](#getPatchSize--) | Ottiene la dimensione del patch (deve essere dispari). |
| [setPatchSize(byte value)](#setPatchSize-byte-) | Imposta la dimensione del patch (deve essere dispari). |
| [getMaxPaintingAttempts()](#getMaxPaintingAttempts--) | Ottiene il numero massimo di tentativi di pittura. |
| [setMaxPaintingAttempts(int value)](#setMaxPaintingAttempts-int-) | Imposta il numero massimo di tentativi di pittura. |
| [getInterestArea()](#getInterestArea--) | Ottiene l'area da cui prelevare i patch. |
| [setInterestArea(Rectangle value)](#setInterestArea-com.aspose.imaging.Rectangle-) | Imposta l'area da cui prelevare i patch. |

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


Inizializza una nuova istanza della classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | La maschera per l'area sconosciuta. |

### ContentAwareFillWatermarkOptions(GraphicsPath mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public ContentAwareFillWatermarkOptions(GraphicsPath mask)
```


Inizializza una nuova istanza della classe [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | La maschera per l'area sconosciuta. |

### getPatchSize() {#getPatchSize--}
```
public final byte getPatchSize()
```


Ottiene la dimensione del patch (deve essere dispari).

Valore: La dimensione del patch.

**Returns:**
byte - la dimensione del patch (deve essere dispari).
### setPatchSize(byte value) {#setPatchSize-byte-}
```
public final void setPatchSize(byte value)
```


Imposta la dimensione del patch (deve essere dispari).

Valore: La dimensione del patch.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | la dimensione del patch (deve essere dispari). |

### getMaxPaintingAttempts() {#getMaxPaintingAttempts--}
```
public final int getMaxPaintingAttempts()
```


Ottiene il numero massimo di tentativi di pittura. L'algoritmo sceglierà la variante migliore.

Valore: Il numero massimo di tentativi di pittura.

**Returns:**
int - il numero massimo di tentativi di pittura.

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


Imposta il numero massimo di tentativi di pittura. L'algoritmo sceglierà la variante migliore.

Valore: Il numero massimo di tentativi di pittura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il numero massimo di tentativi di pittura. |


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


Ottiene l'area da cui prelevare i patch.

Valore: L'area di interesse per prelevare i frammenti.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the area to take patches.
### setInterestArea(Rectangle value) {#setInterestArea-com.aspose.imaging.Rectangle-}
```
public final void setInterestArea(Rectangle value)
```


Imposta l'area da cui prelevare i patch.

Valore: L'area di interesse per prelevare i frammenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | l'area per prelevare i frammenti. |

