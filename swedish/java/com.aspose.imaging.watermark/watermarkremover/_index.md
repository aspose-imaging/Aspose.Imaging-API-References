---
title: "WatermarkRemover"
second_title: "Aspose.Imaging för Java API-referens"
description: "Klassen avsedd för att manipulera vattenstämpeln."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.watermark/watermarkremover/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkRemover
```

Klassen avsedd för att manipulera vattenstämpeln.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [paintOver(RasterImage source, WatermarkOptions options)](#paintOver-com.aspose.imaging.RasterImage-com.aspose.imaging.watermark.options.WatermarkOptions-) | Ta bort vattenstämpeln från rasterbilden. |

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

### paintOver(RasterImage source, WatermarkOptions options) {#paintOver-com.aspose.imaging.RasterImage-com.aspose.imaging.watermark.options.WatermarkOptions-}
```
public static RasterImage paintOver(RasterImage source, WatermarkOptions options)
```


Ta bort vattenstämpeln från rasterbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Den ursprungliga rasterbilden. |
| options | [WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions) | Vattenstämpelalternativen. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The resulting image.
