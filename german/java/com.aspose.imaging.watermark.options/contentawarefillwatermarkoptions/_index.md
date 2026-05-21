---
title: "ContentAwareFillWatermarkOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die gängigen Optionen des Content Aware Fill-Algorithmus."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class ContentAwareFillWatermarkOptions extends WatermarkOptions
```

Die gängigen Optionen des Content Aware Fill-Algorithmus.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ContentAwareFillWatermarkOptions(Point[] mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---) | Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) Klasse. |
| [ContentAwareFillWatermarkOptions(GraphicsPath mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPatchSize()](#getPatchSize--) | Gibt die Patch-Größe zurück (sollte ungerade sein). |
| [setPatchSize(byte value)](#setPatchSize-byte-) | Legt die Patch-Größe fest (sollte ungerade sein). |
| [getMaxPaintingAttempts()](#getMaxPaintingAttempts--) | Gibt die maximale Anzahl von Malversuchen zurück. |
| [setMaxPaintingAttempts(int value)](#setMaxPaintingAttempts-int-) | Legt die maximale Anzahl von Malversuchen fest. |
| [getInterestArea()](#getInterestArea--) | Gibt den Bereich zum Entnehmen von Patches zurück. |
| [setInterestArea(Rectangle value)](#setInterestArea-com.aspose.imaging.Rectangle-) | Legt den Bereich zum Entnehmen von Patches fest. |

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


Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Die Maske für den unbekannten Bereich. |

### ContentAwareFillWatermarkOptions(GraphicsPath mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public ContentAwareFillWatermarkOptions(GraphicsPath mask)
```


Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Die Maske für den unbekannten Bereich. |

### getPatchSize() {#getPatchSize--}
```
public final byte getPatchSize()
```


Gibt die Patch-Größe zurück (sollte ungerade sein).

Wert: Die Größe des Patches.

**Returns:**
byte - die Patch-Größe (sollte ungerade sein).
### setPatchSize(byte value) {#setPatchSize-byte-}
```
public final void setPatchSize(byte value)
```


Legt die Patch-Größe fest (sollte ungerade sein).

Wert: Die Größe des Patches.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | die Patch-Größe (sollte ungerade sein). |

### getMaxPaintingAttempts() {#getMaxPaintingAttempts--}
```
public final int getMaxPaintingAttempts()
```


Gibt die maximale Anzahl von Malversuchen zurück. Der Algorithmus wählt die beste Variante aus.

Wert: Die maximale Anzahl von Malversuchen.

**Returns:**
int - die maximale Anzahl von Malversuchen.

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


Legt die maximale Anzahl von Malversuchen fest. Der Algorithmus wählt die beste Variante.

Wert: Die maximale Anzahl von Malversuchen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die maximale Anzahl von Malversuchen. |


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


Gibt den Bereich zum Entnehmen von Patches zurück.

Wert: Das Interessengebiet zum Erfassen von Patches.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the area to take patches.
### setInterestArea(Rectangle value) {#setInterestArea-com.aspose.imaging.Rectangle-}
```
public final void setInterestArea(Rectangle value)
```


Legt den Bereich zum Entnehmen von Patches fest.

Wert: Das Interessengebiet zum Erfassen von Patches.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | der Bereich zum Erfassen von Patches. |

