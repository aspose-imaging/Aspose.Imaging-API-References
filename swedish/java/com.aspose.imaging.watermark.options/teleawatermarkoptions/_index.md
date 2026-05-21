---
title: "TeleaWatermarkOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "De vanliga Telea‑algoritmalternativen."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

De vanliga Telea‑algoritmalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | Initierar en ny instans av klassen [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Initierar en ny instans av klassen [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | Hämtar halva patch-storleken. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | Ställer in halva patch-storleken. |

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


Initierar en ny instans av klassen [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Masken för det okända området. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


Initierar en ny instans av klassen [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Masken för det okända området. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


Hämtar halva patch-storleken.

Värde: Patch-storleken.

**Returns:**
int - halva patch-storleken.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


Ställer in halva patch-storleken.

Värde: Patch-storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | halva patch-storleken. |

