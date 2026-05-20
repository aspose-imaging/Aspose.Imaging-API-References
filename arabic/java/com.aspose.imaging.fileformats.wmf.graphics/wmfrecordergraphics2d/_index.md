---
title: "WmfRecorderGraphics2D"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "مسجل Wmf."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class WmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

مسجل Wmf.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfRecorderGraphics2D(Rectangle frame, int inch)](#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-) | يُهيئ نسخة جديدة من الفئة `WmfRecorderGraphics2D`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | يحصل أو يعيّن وضع الخلفية. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | يحصل أو يعيّن وضع الخلفية. |
| [endRecording()](#endRecording--) | ينهي التسجيل. |
| [fromWmfImage(WmfImage wmfImage)](#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-) | يحصل على نسخة من مسجل Wmf لصورة Wmf الحالية. |

## Example: This example shows how to create a WMF image and draw some geometric shapes using WmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// هذه هي دقة الشاشة الافتراضية.
int dpi = 96;

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight);

// إنشاء صورة WMF.
com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D(frame, dpi);

// ارسم مستطيلًا أسود على حدود الصورة باستخدام قلم أسود بعرض بكسل واحد.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// املأ مستطيلًا بلون الدخان الأبيض.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// ارسم خطين قطريين باستخدام قلم أخضر داكن بعرض بكسل واحد.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// ارسم قوسًا داخل المستطيل {0, 0, 200, 200} باستخدام قلم أزرق بعرض بكسلين.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// املأ قوسًا
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// ارسم منحنى بيزيه مكعب باستخدام قلم أحمر بعرض بكسلين.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// ارسم صورة نقطية بالحجم المحدد في الموقع المحدد.
// يتم تحجيم الصورة لتناسب المستطيل المطلوب.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
{
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
}

// ارسم سلسلة نصية
graphics.drawString("Hello World!", new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular), com.aspose.imaging.Color.getDarkRed(), 200, 300);

// إنشاء مسار للتعبئة
com.aspose.imaging.Figure figureToFill = new com.aspose.imaging.Figure();
figureToFill.setClosed(true);

com.aspose.imaging.GraphicsPath pathToFill = new com.aspose.imaging.GraphicsPath();
pathToFill.addFigure(figureToFill);

figureToFill.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(400, 0, 200, 100), 45, 300),
                new com.aspose.imaging.shapes.BezierShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 200),
                                        new com.aspose.imaging.PointF(400, 200),
                                        new com.aspose.imaging.PointF(500, 100),
                                        new com.aspose.imaging.PointF(600, 200),
                                }),
                new com.aspose.imaging.shapes.PolygonShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 100),
                                }),
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
        });

// املأ المسار باستخدام فرشاة صفراء وقلم أخضر لرسم الحدود.
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// إنشاء مسار للرسم
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// ارسم المسار باستخدام قلم برتقالي بعرض 5 بكسلات.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// من أجل تحويل SVG إلى نقطية، نحتاج إلى تحديد خيارات التحويل النقطي.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// احصل على صورة WMF النهائية التي تشمل جميع أوامر الرسم.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = graphics.endRecording();
try {
    wmfImage.save(dir + "test.output.wmf");
} finally {
    wmfImage.dispose();
}
```

### WmfRecorderGraphics2D(Rectangle frame, int inch) {#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-}
```
public WmfRecorderGraphics2D(Rectangle frame, int inch)
```


يُهيئ نسخة جديدة من الفئة `WmfRecorderGraphics2D`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الوجهة، مقاسًا بوحدات twips، لعرض ملف التعريف. |
| بوصة | int | عدد البكسلات لكل بوصة. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


يحصل أو يعيّن وضع الخلفية.

القيمة: وضع الخلفية.

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


يحصل أو يعيّن وضع الخلفية.

القيمة: وضع الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### endRecording() {#endRecording--}
```
public WmfImage endRecording()
```


ينهي التسجيل.

**Returns:**
[WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) - The result image.
### fromWmfImage(WmfImage wmfImage) {#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-}
```
public static WmfRecorderGraphics2D fromWmfImage(WmfImage wmfImage)
```


يحصل على نسخة من مسجل Wmf لصورة Wmf الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| wmfImage | [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) | صورة Wmf التي تريد الحصول على مسجل لها. |

**Returns:**
[WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) - An instance of the [WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) class.
