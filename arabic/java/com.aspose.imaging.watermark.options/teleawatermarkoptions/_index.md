---
title: "TeleaWatermarkOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات خوارزمية Telea الشائعة."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

خيارات خوارزمية Telea الشائعة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | ينشئ مثلاً جديداً من الفئة [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | ينشئ مثلاً جديداً من الفئة [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | يحصل على نصف حجم الرقعة. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | يضبط نصف حجم الرقعة. |

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


ينشئ مثلاً جديداً من الفئة [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | القناع للمنطقة غير المعروفة. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


ينشئ مثلاً جديداً من الفئة [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | القناع للمنطقة غير المعروفة. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


يحصل على نصف حجم الرقعة.

القيمة: حجم الرقعة.

**Returns:**
int - نصف حجم الرقعة.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


يضبط نصف حجم الرقعة.

القيمة: حجم الرقعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نصف حجم الرقعة. |

