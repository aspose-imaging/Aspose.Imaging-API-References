---
title: "ContentAwareFillWatermarkOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "De vanliga Content Aware Fill‑algoritmalternativen."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class ContentAwareFillWatermarkOptions extends WatermarkOptions
```

De vanliga Content Aware Fill‑algoritmalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ContentAwareFillWatermarkOptions(Point[] mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---) | Initierar en ny instans av klassen [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
| [ContentAwareFillWatermarkOptions(GraphicsPath mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Initierar en ny instans av klassen [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPatchSize()](#getPatchSize--) | Hämtar patch-storleken (bör vara udda). |
| [setPatchSize(byte value)](#setPatchSize-byte-) | Ställer in patch-storleken (bör vara udda). |
| [getMaxPaintingAttempts()](#getMaxPaintingAttempts--) | Hämtar maximalt antal målningsförsök. |
| [setMaxPaintingAttempts(int value)](#setMaxPaintingAttempts-int-) | Ställer in maximalt antal målningsförsök. |
| [getInterestArea()](#getInterestArea--) | Hämtar området för att ta patchar. |
| [setInterestArea(Rectangle value)](#setInterestArea-com.aspose.imaging.Rectangle-) | Ställer in området för att ta patchar. |

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


Initierar en ny instans av klassen [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Masken för det okända området. |

### ContentAwareFillWatermarkOptions(GraphicsPath mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public ContentAwareFillWatermarkOptions(GraphicsPath mask)
```


Initierar en ny instans av klassen [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Masken för det okända området. |

### getPatchSize() {#getPatchSize--}
```
public final byte getPatchSize()
```


Hämtar patch-storleken (bör vara udda).

Värde: Storleken på patchen.

**Returns:**
byte - patch-storleken (bör vara udda).
### setPatchSize(byte value) {#setPatchSize-byte-}
```
public final void setPatchSize(byte value)
```


Ställer in patch-storleken (bör vara udda).

Värde: Storleken på patchen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | patch-storleken (bör vara udda). |

### getMaxPaintingAttempts() {#getMaxPaintingAttempts--}
```
public final int getMaxPaintingAttempts()
```


Hämtar maximalt antal målningsförsök. Algoritmen kommer att välja det bästa alternativet.

Värde: Det maximala antalet målningförsök.

**Returns:**
int - det maximala antalet målningförsök.

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


Ställer in det maximala antalet målningförsök. Algoritmen kommer att välja det bästa alternativet.

Värde: Det maximala antalet målningförsök.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | det maximala antalet målningförsök. |


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


Hämtar området för att ta patchar.

Värde: Området av intresse för att ta patchar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the area to take patches.
### setInterestArea(Rectangle value) {#setInterestArea-com.aspose.imaging.Rectangle-}
```
public final void setInterestArea(Rectangle value)
```


Ställer in området för att ta patchar.

Värde: Området av intresse för att ta patchar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | området för att ta patchar. |

