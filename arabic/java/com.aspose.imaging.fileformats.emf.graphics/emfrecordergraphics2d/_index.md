---
title: "EmfRecorderGraphics2D"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "رسومات مسجل Emf"
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class EmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

رسومات مسجل Emf
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)](#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-) | يُنشئ مثيلًا جديدًا من الفئة `EmfRecorderGraphics2D`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | يحصل أو يعيّن وضع الخلفية. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | يحصل أو يعيّن وضع الخلفية. |
| [endRecording()](#endRecording--) | ينهي التسجيل. |
| [fromEmfImage(EmfImage emfImage)](#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-) | يحصل على مثيل من [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) يحتوي على جميع السجلات من صورة Emf. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// حجم الصورة بالبكسل
int deviceWidth = 600;
int deviceHeight = 400;

// حجم الصورة بالمليمتر
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// إنشاء صورة EMF.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// ارسم مستطيلًا أسود على حدود الصورة باستخدام قلم أسود بعرض بكسل واحد.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// املأ مستطيلًا بلون دخان أبيض.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// ارسم خطين قطريين باستخدام قلم أخضر داكن بعرض بكسل واحد.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// ارسم قوسًا داخل المستطيل {0, 0, 200, 200} باستخدام قلم أزرق بعرض بكسلين.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// املأ قوسًا
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// ارسم منحنى بيزير مكعب باستخدام قلم أحمر بعرض بكسلين.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// ارسم صورة نقطية بالحجم المحدد في الموقع المحدد.
// يتم تحجيم الصورة لتناسب المستطيل المطلوب.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// ارسم سلسلة نصية
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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

// ارسم المسار باستخدام قلم برتقالي بعرض 5 بكسل.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// من أجل تحويل SVG إلى نقطية نحتاج إلى تحديد خيارات التحويل إلى نقطية.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// احصل على صورة WMF النهائية التي تتضمن جميع أوامر الرسم
com.aspose.imaging.fileformats.emf.EmfImage emfImage = graphics.endRecording();
try {
    emfImage.save(dir + "test.output.emf");
} finally {
    emfImage.dispose();
}
```

### EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm) {#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfRecorderGraphics2D`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | الإطار. |
| deviceSize | [Size](../../com.aspose.imaging/size) | حجم الجهاز. |
| deviceSizeMm | [Size](../../com.aspose.imaging/size) | حجم الجهاز بالمليمتر. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


يحصل أو يعيّن وضع الخلفية.

**Returns:**
int - وضع الخلفية.
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


يحصل أو يعيّن وضع الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | وضع الخلفية. |

### endRecording() {#endRecording--}
```
public EmfImage endRecording()
```


ينهي التسجيل.

**Returns:**
[EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) - The result image.
### fromEmfImage(EmfImage emfImage) {#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-}
```
public static EmfRecorderGraphics2D fromEmfImage(EmfImage emfImage)
```


يحصل على مثيل من [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) يحتوي على جميع السجلات من صورة Emf.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| emfImage | [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) | صورة Emf لقراءة السجلات منها. |

**Returns:**
[EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) - An instance of the [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d)

**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // أولاً، احصل على حجم الصورة
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // ثانياً، احسب تحويلًا لوضع سلسلة نصية على القطر الرئيسي للصورة -
    // من الزاوية العليا اليسرى إلى الزاوية السفلى اليمنى.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // ثم، اضبط التحويل.
    graphics.setTransform(transform);

    // أخيرًا، ضع علامة مائية (سلسلة نصية باللون الوردي) على القطر الرئيسي.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // احفظ الصورة مع العلامة المائية إلى ملف EMF آخر.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

