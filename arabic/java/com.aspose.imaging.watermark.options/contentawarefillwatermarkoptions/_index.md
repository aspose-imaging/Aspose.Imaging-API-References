---
title: "ContentAwareFillWatermarkOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات خوارزمية التعبئة الواعية بالمحتوى الشائعة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class ContentAwareFillWatermarkOptions extends WatermarkOptions
```

خيارات خوارزمية التعبئة الواعية بالمحتوى الشائعة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ContentAwareFillWatermarkOptions(Point[] mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---) | ينشئ مثلاً جديداً من الفئة [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
| [ContentAwareFillWatermarkOptions(GraphicsPath mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-) | ينشئ مثلاً جديداً من الفئة [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPatchSize()](#getPatchSize--) | يحصل على حجم الرقعة (يجب أن يكون فرديًا). |
| [setPatchSize(byte value)](#setPatchSize-byte-) | يضبط حجم الرقعة (يجب أن يكون فرديًا). |
| [getMaxPaintingAttempts()](#getMaxPaintingAttempts--) | يحصل على الحد الأقصى لعدد محاولات الرسم. |
| [setMaxPaintingAttempts(int value)](#setMaxPaintingAttempts-int-) | يضبط الحد الأقصى لعدد محاولات الرسم. |
| [getInterestArea()](#getInterestArea--) | يحصل على المنطقة لاستخراج الرقع. |
| [setInterestArea(Rectangle value)](#setInterestArea-com.aspose.imaging.Rectangle-) | يضبط المنطقة لاستخراج الرقع. |

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


ينشئ مثلاً جديداً من الفئة [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | القناع للمنطقة غير المعروفة. |

### ContentAwareFillWatermarkOptions(GraphicsPath mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public ContentAwareFillWatermarkOptions(GraphicsPath mask)
```


ينشئ مثلاً جديداً من الفئة [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | القناع للمنطقة غير المعروفة. |

### getPatchSize() {#getPatchSize--}
```
public final byte getPatchSize()
```


يحصل على حجم الرقعة (يجب أن يكون فرديًا).

القيمة: حجم الرقعة.

**Returns:**
byte - حجم الرقعة (يجب أن يكون فرديًا).
### setPatchSize(byte value) {#setPatchSize-byte-}
```
public final void setPatchSize(byte value)
```


يضبط حجم الرقعة (يجب أن يكون فرديًا).

القيمة: حجم الرقعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | حجم الرقعة (يجب أن يكون فرديًا). |

### getMaxPaintingAttempts() {#getMaxPaintingAttempts--}
```
public final int getMaxPaintingAttempts()
```


يحصل على الحد الأقصى لعدد محاولات الرسم. ستختار الخوارزمية أفضل بديل.

القيمة: الحد الأقصى لعدد محاولات الرسم.

**Returns:**
int - الحد الأقصى لعدد محاولات الرسم.

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


يضبط الحد الأقصى لعدد محاولات الرسم. سيختار الخوارزمية أفضل خيار.

القيمة: الحد الأقصى لعدد محاولات الرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الحد الأقصى لعدد محاولات الرسم. |


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


يحصل على المنطقة لاستخراج الرقع.

القيمة: المنطقة المستهدفة لأخذ القطع.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the area to take patches.
### setInterestArea(Rectangle value) {#setInterestArea-com.aspose.imaging.Rectangle-}
```
public final void setInterestArea(Rectangle value)
```


يضبط المنطقة لاستخراج الرقع.

القيمة: المنطقة المستهدفة لأخذ القطع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | المنطقة لأخذ القطع. |

