---
title: "WatermarkRemover"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс, предназначенный для манипулирования водяным знаком."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.watermark/watermarkremover/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkRemover
```

Класс, предназначенный для манипулирования водяным знаком.
## Методы

| Метод | Описание |
| --- | --- |
| [paintOver(RasterImage source, WatermarkOptions options)](#paintOver-com.aspose.imaging.RasterImage-com.aspose.imaging.watermark.options.WatermarkOptions-) | Удаляет водяной знак с растрового изображения. |

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


Удаляет водяной знак с растрового изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Исходное растровое изображение. |
| options | [WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions) | Параметры водяного знака. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The resulting image.
