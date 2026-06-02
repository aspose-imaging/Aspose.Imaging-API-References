---
title: "ArcShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل شكل القوس."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.shapes/arcshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape), [com.aspose.imaging.shapes.PieShape](../../com.aspose.imaging.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

يمثل شكل القوس.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ArcShape()](#ArcShape--) | يُنشئ مثيلاً جديدًا من الفئة `ArcShape`. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.imaging.RectangleF-float-float-) | يُنشئ مثيلاً جديدًا من الفئة `ArcShape`. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-) | يُنشئ مثيلاً جديدًا من الفئة `ArcShape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [getStartPoint()](#getStartPoint--) | يحصل على نقطة بدء الشكل. |
| [getEndPoint()](#getEndPoint--) | يحصل على نقطة نهاية الشكل. |
| [isClosed()](#isClosed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. |
| [setClosed(boolean value)](#setClosed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. |
| [reverse()](#reverse--) | يعكس ترتيب النقاط لهذا الشكل. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
هذا المثال ينشئ صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures و GraphicsPath على سطح الصورة.
``` java
//ينشئ مثيلاً من BmpOptions ويضبط خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
//المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//إنشاء نسخة من Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //إنشاء وتهيئة نسخة من فئة Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //مسح سطح Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //إنشاء نسخة من فئة GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //إنشاء نسخة من فئة Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //إضافة شكل إلى كائن Figure.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //إنشاء نسخة من فئة Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //إضافة شكل إلى كائن Figure.
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //رسم مسار باستخدام كائن Pen باللون الأسود
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // احفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### ArcShape() {#ArcShape--}
```
public ArcShape()
```


يُنشئ مثيلاً جديدًا من الفئة `ArcShape`.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.imaging.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


يُنشئ مثيلاً جديدًا من الفئة `ArcShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل. |
| startAngle | float | زاوية البداية. |
| sweepAngle | float | زاوية القطع. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


يُنشئ مثيلاً جديدًا من الفئة `ArcShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل. |
| startAngle | float | زاوية البداية. |
| sweepAngle | float | زاوية القطع. |
| isClosed | boolean | إذا تم تعيينه إلى `true` يصبح القوس مغلقًا. القوس المغلق يتحول فعليًا إلى إهليلج. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل.

القيمة: مقاطع الشكل.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


يحصل على نقطة بدء الشكل.

القيمة: نقطة بداية الشكل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


يحصل على نقطة نهاية الشكل.

القيمة: نقطة نهاية الشكل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة الشكل المرتب المغلق لا يكون للنقطة البداية والنهاية أي معنى.

القيمة: `True` إذا كان هذا الشكل المرتب مغلقًا؛ وإلا `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة الشكل المرتب المغلق لا يكون للنقطة البداية والنهاية أي معنى.

القيمة: `True` إذا كان هذا الشكل المرتب مغلقًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### reverse() {#reverse--}
```
public void reverse()
```


يعكس ترتيب النقاط لهذا الشكل.

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن الآخر. |

**Returns:**
boolean - نتيجة مقارنة المساواة.
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int - رمز التجزئة.
