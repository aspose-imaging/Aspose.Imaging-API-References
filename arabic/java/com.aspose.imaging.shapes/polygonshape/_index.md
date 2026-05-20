---
title: "PolygonShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل شكل مضلع."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

يمثل شكل مضلع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | يقوم بإنشاء مثيل جديد لفئة `PolygonShape`. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | يقوم بإنشاء مثيل جديد لفئة `PolygonShape`. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | يقوم بإنشاء مثيل جديد لفئة `PolygonShape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPoints()](#getPoints--) | يحصل أو يعيّن نقاط المنحنى. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | يحصل أو يعيّن نقاط المنحنى. |
| [isClosed()](#isClosed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| [setClosed(boolean value)](#setClosed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| [getBounds()](#getBounds--) | يحصل على حدود الكائن. |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [getStartPoint()](#getStartPoint--) | يحصل على نقطة بدء الشكل. |
| [getEndPoint()](#getEndPoint--) | يحصل على نقطة نهاية الشكل. |
| [reverse()](#reverse--) | يعكس ترتيب النقاط لهذا الشكل. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | يحصل على حدود الكائن. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة التجزئة الافتراضية. |

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

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


يقوم بإنشاء مثيل جديد لفئة `PolygonShape`.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


يقوم بإنشاء مثيل جديد لفئة `PolygonShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


يقوم بإنشاء مثيل جديد لفئة `PolygonShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |
| isClosed | boolean | إذا تم تعيينه إلى `true` فإن المضلع مغلق. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


يحصل أو يعيّن نقاط المنحنى.

القيمة: نقاط المنحنى.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


يحصل أو يعيّن نقاط المنحنى.

القيمة: نقاط المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا.

القيمة: `true` إذا كان الشكل مغلقًا؛ وإلا `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا.

القيمة: `true` إذا كان الشكل مغلقًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


يحصل على حدود الكائن.

القيمة: حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


يحصل على مركز الشكل.

القيمة: مركز الشكل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل.

القيمة: مقاطع الشكل.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع.

القيمة: `True` إذا كان الشكل يحتوي على مقاطع؛ وإلا `false`.

**Returns:**
boolean
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
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


يطبق التحويل المحدد على الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | التحويل المراد تطبيقه. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن المقارن. |

**Returns:**
منطقي - نتيجة equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة التجزئة الافتراضية.

**Returns:**
عدد صحيح - رمز تجزئة للكائن الحالي.
