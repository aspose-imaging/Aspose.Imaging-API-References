---
title: TeleaWatermarkOptions
second_title: Aspose.Imaging for Java API Reference
description: The common Telea Algorithm options.
type: docs
weight: 11
url: /com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

The common Telea Algorithm options.
## Constructors

| Constructor | Description |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | Initializes a new instance of the [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) class. |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Initializes a new instance of the [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | Gets the half patch size. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | Sets the half patch size. |

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


Initializes a new instance of the [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | The mask for the unknown area. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


Initializes a new instance of the [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The mask for the unknown area. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


Gets the half patch size.

Value: The patch size.

**Returns:**
int - the half patch size.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


Sets the half patch size.

Value: The patch size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the half patch size. |

