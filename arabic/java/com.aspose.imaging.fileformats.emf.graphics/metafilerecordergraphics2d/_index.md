---
title: "MetafileRecorderGraphics2D"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "رسومات مسجل ملفات ميتا"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

رسومات مسجل ملفات ميتا
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getClip()](#getClip--) | يحصل أو يضبط Region التي تحدد منطقة الرسم لهذا Graphics |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | يحصل أو يضبط Region التي تحدد منطقة الرسم لهذا Graphics |
| [getClipBounds()](#getClipBounds--) | يحصل على clip bounds. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يضبط لون الخلفية. |
| [clear()](#clear--) | يمسح حالة كائن graphics |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | يرسم منحنى بيزير مكعب. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | يرسم منحنى بيزير مكعب متعدد. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | يرسم الإهليلج. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | يملأ الإهليلج. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | يرسم الصورة. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | يرسم الصورة. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | يرسم الخط. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | يرسم الخط. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | يرسم الخط المتعدد. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | يرسم المسار. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | يملأ المسار. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | يرسم الفطيرة. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | يملأ الفطيرة. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | يرسم المضلع. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | يملأ المضلع. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | يملأ المضلع. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | يرسم المستطيل. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | يرسم المستطيل. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | يملأ المستطيل. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | يرسم النص. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | يرسم النص. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة بنية مستطيل. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة منطقة. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | يقوم بتحديث منطقة القص لهذه الرسومات لتصبح تقاطع منطقة القص الحالية والبنية المستطيلة المحددة. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | يقوم بتحديث منطقة القص لهذه الرسومات لتصبح تقاطع منطقة القص الحالية والمنطقة المحددة. |
| [resetClip()](#resetClip--) | يعيد تعيين القص. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة بالترتيب المحدد. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | يغيّر أصل نظام الإحداثيات بإلحاق الترجمة المحددة إلى مصفوفة التحويل لهذه الرسومات. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | يغيّر أصل نظام الإحداثيات بتطبيق الترجمة المحددة على مصفوفة التحويل لهذه الرسومات بالترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يطبق الدوران المحدد على مصفوفة التحويل لهذه الرسومات. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | يطبق الدوران المحدد على مصفوفة التحويل لهذه الرسومات بالترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يطبق عملية التحجيم المحددة على مصفوفة التحويل الخاصة بهذا Graphics عن طريق إضافتها في بداية مصفوفة التحويل الخاصة بالكائن. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يطبق عملية التحجيم المحددة على مصفوفة التحويل الخاصة بهذا Graphics بالترتيب المحدد. |
| [getTransform()](#getTransform--) | يحصل على تحويل العالم. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | يضبط التحويل. |

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

### MetafileRecorderGraphics2D() {#MetafileRecorderGraphics2D--}
```
public MetafileRecorderGraphics2D()
```


### getClip() {#getClip--}
```
public Region getClip()
```


يحصل أو يضبط Region التي تحدد منطقة الرسم لهذا Graphics

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


يحصل أو يضبط Region التي تحدد منطقة الرسم لهذا Graphics

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | منطقة القص. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


يحصل على clip bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الخلفية.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يضبط لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### clear() {#clear--}
```
public void clear()
```


يمسح حالة كائن graphics

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | حدود القطع الناقص. |
| startAngle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| arcAngle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من معلمة startAngle إلى نقطة النهاية للقوس. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


يرسم منحنى بيزير مكعب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| pt1 | [Point](../../com.aspose.imaging/point) | نقطة البداية للمنحنى. |
| pt2 | [Point](../../com.aspose.imaging/point) | نقطة التحكم الأولى للمنحنى. |
| pt3 | [Point](../../com.aspose.imaging/point) | نقطة التحكم الثانية للمنحنى. |
| pt4 | [Point](../../com.aspose.imaging/point) | نقطة النهاية للمنحنى. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


يرسم منحنى بيزير مكعب متعدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| points | [Point\[\]](../../com.aspose.imaging/point) | النقاط. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


يرسم الإهليلج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | حدود القطع الناقص. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


يملأ الإهليلج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | فرشاة تحدد خصائص التعبئة. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | حدود القطع الناقص. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة المراد رسمها. |
| location | [Point](../../com.aspose.imaging/point) | موقع الزاوية العلوية اليسرى للصورة المرسومة. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


يرسم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageBytes | byte[] | بايتات الصورة. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل الوجهة. |
| srcUnit | int | وحدة المصدر. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


يرسم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل الوجهة. |
| srcUnit | int | وحدة المصدر. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة المراد رسمها. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل المستطيل الذي يحدد موقع وحجم الصورة المرسومة. يتم تحجيم الصورة لتناسب المستطيل. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل المستطيل الذي يحدد الجزء من كائن الصورة المراد رسمه. |
| srcUnit | int | وحدات القياس المستخدمة بواسطة معلمة srcRect. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


يرسم الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| x1 | int | الإحداثي السيني للنقطة الأولى. |
| y1 | int | الإحداثي الصادي للنقطة الأولى. |
| x2 | int | الإحداثي السيني للنقطة الثانية. |
| y2 | int | الإحداثي الصادي للنقطة الثانية. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


يرسم الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| pt1 | [Point](../../com.aspose.imaging/point) | النقطة الأولى. |
| pt2 | [Point](../../com.aspose.imaging/point) | النقطة الثانية. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


يرسم الخط المتعدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| points | [Point\[\]](../../com.aspose.imaging/point) | النقاط. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


يرسم المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | المسار للرسم. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


يملأ المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| brush | [Brush](../../com.aspose.imaging/brush) | فرشاة تحدد خصائص التعبئة. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | المسار للتعبئة. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


يرسم الفطيرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | حدود القطع الناقص. |
| startAngle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweepAngle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من معلمة startAngle إلى نقطة النهاية للقوس. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


يملأ الفطيرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | فرشاة تحدد خصائص التعبئة. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | حدود القطع الناقص. |
| startAngle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweepAngle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من معلمة startAngle إلى نقطة النهاية للقوس. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


يرسم المضلع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| points | [Point\[\]](../../com.aspose.imaging/point) | النقاط. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


يملأ المضلع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | فرشاة تحدد خصائص التعبئة. |
| points | [Point\[\]](../../com.aspose.imaging/point) | النقاط. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


يملأ المضلع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | فرشاة تحدد خصائص التعبئة. |
| points | [Point\[\]](../../com.aspose.imaging/point) | النقاط. |
| fillMode | int | وضع التعبئة. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


يرسم المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


يرسم المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | قلم يحدد اللون والعرض والنمط للشكل. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المراد رسمه. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


يملأ المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | فرشاة تحدد خصائص التعبئة. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المراد تعبئته. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


يرسم النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| سلسلة | java.lang.String | السلسلة. |
| font | [Font](../../com.aspose.imaging/font) | الخط الذي يحدد تنسيق النص للسلسلة. |
| color | [Color](../../com.aspose.imaging/color) | لون النص. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للنص المرسوم. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للنص المرسوم. |


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

### drawString(String string, Font font, Color color, int x, int y, float angle) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-}
```
public void drawString(String string, Font font, Color color, int x, int y, float angle)
```


يرسم النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| سلسلة | java.lang.String | السلسلة. |
| font | [Font](../../com.aspose.imaging/font) | الخط الذي يحدد تنسيق النص للسلسلة. |
| color | [Color](../../com.aspose.imaging/color) | لون النص. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للنص المرسوم. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للنص المرسوم. |
| angle | float | الزاوية بالدرجات بين متجه الإزاحة ومحور x للجهاز. متجه الإزاحة موازٍ لخط الأساس لسطر من النص. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة بنية مستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | بنية المستطيل التي تحدد المستطيل لاستبعاده من منطقة القص. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة منطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | المنطقة التي تحدد المنطقة لاستبعاده من منطقة القص. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


يقوم بتحديث منطقة القص لهذه الرسومات لتصبح تقاطع منطقة القص الحالية والبنية المستطيلة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | بنية المستطيل للتقاطع مع منطقة القص الحالية. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


يقوم بتحديث منطقة القص لهذه الرسومات لتصبح تقاطع منطقة القص الحالية والمنطقة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | المنطقة للتقاطع مع المنطقة الحالية. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


يعيد تعيين القص.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة التي تضرب تحويل العالم. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة التي تضرب تحويل العالم. |
| الترتيب | int | ترتيب الضرب. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


يغيّر أصل نظام الإحداثيات بإلحاق الترجمة المحددة إلى مصفوفة التحويل لهذه الرسومات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للترجمة. |
| y | float | الإحداثي الصادي للترجمة. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


يغيّر أصل نظام الإحداثيات بتطبيق الترجمة المحددة على مصفوفة التحويل لهذه الرسومات بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للترجمة. |
| y | float | الإحداثي الصادي للترجمة. |
| الترتيب | int | يحدد ما إذا كانت الترجمة تُضاف في البداية أو في النهاية إلى مصفوفة التحويل. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يطبق الدوران المحدد على مصفوفة التحويل لهذه الرسومات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


يطبق الدوران المحدد على مصفوفة التحويل لهذه الرسومات بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. |
| center | [PointF](../../com.aspose.imaging/pointf) | مركز الدوران. |
| الترتيب | int | يحدد ما إذا كان الدوران يُضاف في النهاية أو يُسبق إلى تحويل المصفوفة. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يطبق عملية التحجيم المحددة على مصفوفة التحويل الخاصة بهذا Graphics عن طريق إضافتها في بداية مصفوفة التحويل الخاصة بالكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | عامل المقياس في الاتجاه السيني. |
| sy | float | عامل المقياس في الاتجاه الصادي. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يطبق عملية التحجيم المحددة على مصفوفة التحويل الخاصة بهذا Graphics بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | عامل المقياس في الاتجاه السيني. |
| sy | float | عامل المقياس في الاتجاه الصادي. |
| الترتيب | int | يحدد ما إذا كانت عملية التحجيم تُسبق أو تُضاف إلى مصفوفة التحويل. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل على تحويل العالم.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


يضبط التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | مصفوفة التحويل الجديدة. |


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

