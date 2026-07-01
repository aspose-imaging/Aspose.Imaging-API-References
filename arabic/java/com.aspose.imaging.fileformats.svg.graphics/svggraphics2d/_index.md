---
title: "SvgGraphics2D"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يوفر أوامر رسم لتكوين صورة Svg."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

يوفر أوامر رسم لتكوين صورة Svg.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | يُنشئ نسخة جديدة من الفئة [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | يُنشئ نسخة جديدة من الفئة [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | يرسم الصورة المحددة في الموقع المحدد. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | يرسم الصورة المحددة بالحجم المحدد في الموقع المحدد. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | يملأ قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | يرسم منحنى بيزير مكعب. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | يرسم سلسلة النص. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | يرسم الخط. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | يرسم المسار. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | يملأ المسار. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | يرسم المستطيل. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | يملأ المستطيل. |
| [endRecording()](#endRecording--) | يحصل على صورة Svg النهائية التي تشمل جميع أوامر الرسم التي تم تنفيذها عبر كائن [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// ارسم مستطيلًا أسود على حدود الصورة باستخدام قلم أسود بعرض بكسل واحد.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// املأ مستطيلًا بلون دخان أبيض.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// ارسم خطين قطريين باستخدام قلم أخضر داكن بعرض بكسل واحد.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// ارسم قوسًا داخل المستطيل {0, 0, 200, 200} باستخدام قلم أزرق بعرض بكسلين.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// املأ قوسًا
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// ارسم منحنى بيزير مكعب باستخدام قلم أحمر بعرض بكسلين.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// ارسم صورة نقطية بالحجم المحدد في الموقع المحدد.
// يتم تحجيم الصورة لتناسب المستطيل المطلوب.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// ارسم سلسلة نصية
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

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
                new com.aspose.imaging.shapes.RectangleShape(
                        new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// احصل على صورة SVG النهائية التي تشمل جميع أوامر الرسم
com.aspose.imaging.fileformats.svg.SvgImage svgImage = graphics.endRecording();
try {
    svgImage.save(dir + "test.output.svg");
} finally {
    svgImage.dispose();
}
```

### SvgGraphics2D(int width, int height, int dpi) {#SvgGraphics2D-int-int-int-}
```
public SvgGraphics2D(int width, int height, int dpi)
```


يُنشئ نسخة جديدة من الفئة [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض صورة Svg الناتجة. |
| height | int | عرض صورة Svg الناتجة. |
| dpi | int | دقة الجهاز، مثال 96 نقطة في البوصة. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


يُنشئ نسخة جديدة من الفئة [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | الصورة التي تُجرى عليها عمليات الرسم. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


يرسم الصورة المحددة في الموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة المرسومة. |
| origin | [Point](../../com.aspose.imaging/point) | موقع الصورة المرسومة. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


يرسم الصورة المحددة بالحجم المحدد في الموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة المرسومة. |
| origin | [Point](../../com.aspose.imaging/point) | موقع الصورة المرسومة. |
| size | [Size](../../com.aspose.imaging/size) | الحجم المطلوب للصورة المرسومة. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | الجزء من كائن الصورة الذي سيتم رسمه. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | الموقع والحجم للصورة المرسومة. يتم تحجيم الصورة لتناسب المستطيل. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة المراد رسمها. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم لرسم حدود الشكل. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | حدود القطع الناقص. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| arcAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من معامل startAngle إلى نقطة نهاية القوس. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


يملأ قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم لرسم حدود الشكل. |
| brush | [Brush](../../com.aspose.imaging/brush) | الفرشاة لملء داخل الشكل. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | حدود القطع الناقص. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| arcAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من معامل startAngle إلى نقطة نهاية القوس. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


يرسم منحنى بيزير مكعب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم الذي يحدد اللون والعرض والنمط للشكل. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | نقطة البداية للمنحنى. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | نقطة التحكم الأولى للمنحنى. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | نقطة التحكم الثانية للمنحنى. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | نقطة النهاية للمنحنى. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


يرسم سلسلة النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | الخط المستخدم لعرض النص. |
| text | java.lang.String | سلسلة النص Unicode. |
| origin | [Point](../../com.aspose.imaging/point) | الزاوية العلوية اليسرى لتشغيل النص. |
| textColor | [Color](../../com.aspose.imaging/color) | لون النص. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


يرسم الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم الذي يحدد اللون والعرض والنمط للشكل. |
| x1 | int | الإحداثي السيني للنقطة الأولى. |
| y1 | int | الإحداثي الصادي للنقطة الأولى. |
| x2 | int | الإحداثي السيني للنقطة الثانية. |
| y2 | int | الإحداثي الصادي للنقطة الثانية. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


يرسم المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم لرسم حدود الشكل. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | المسار للرسم. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


يملأ المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم لرسم حدود الشكل. |
| brush | [Brush](../../com.aspose.imaging/brush) | الفرشاة لملء داخل الشكل. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | المسار للرسم. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


يرسم المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم لرسم حدود الشكل. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


يملأ المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم لرسم حدود الشكل. |
| brush | [Brush](../../com.aspose.imaging/brush) | الفرشاة لملء داخل الشكل. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


يحصل على صورة Svg النهائية التي تشمل جميع أوامر الرسم التي تم تنفيذها عبر كائن [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
