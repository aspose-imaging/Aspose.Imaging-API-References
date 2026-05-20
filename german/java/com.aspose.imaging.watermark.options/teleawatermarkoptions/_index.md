---
title: "TeleaWatermarkOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die gängigen Optionen des Telea-Algorithmus."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

Die gängigen Optionen des Telea-Algorithmus.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | Initialisiert eine neue Instanz der [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) Klasse. |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Initialisiert eine neue Instanz der [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | Gibt die halbe Patch-Größe zurück. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | Legt die halbe Patch-Größe fest. |

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


Initialisiert eine neue Instanz der [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Die Maske für den unbekannten Bereich. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


Initialisiert eine neue Instanz der [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Die Maske für den unbekannten Bereich. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


Gibt die halbe Patch-Größe zurück.

Wert: Die Patch-Größe.

**Returns:**
int - die halbe Patch-Größe.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


Legt die halbe Patch-Größe fest.

Wert: Die Patch-Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die halbe Patch-Größe. |

