---
title: "WatermarkRemover"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe destinata alla manipolazione della filigrana."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.watermark/watermarkremover/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkRemover
```

La classe destinata alla manipolazione della filigrana.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [paintOver(RasterImage source, WatermarkOptions options)](#paintOver-com.aspose.imaging.RasterImage-com.aspose.imaging.watermark.options.WatermarkOptions-) | Rimuove la filigrana dall'immagine raster. |

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


Rimuove la filigrana dall'immagine raster.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster di origine. |
| options | [WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions) | Le opzioni della filigrana. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The resulting image.
