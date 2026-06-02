---
title: "CurveShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل شكل منحنى مقوس."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.shapes/curveshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

يمثل شكل منحنى مقوس.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CurveShape()](#CurveShape--) | ينشئ مثيلًا جديدًا من الفئة `CurveShape`. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.imaging.PointF---) | ينشئ مثيلًا جديدًا من الفئة `CurveShape`. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---boolean-) | ينشئ مثيلًا جديدًا من الفئة `CurveShape`. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.imaging.PointF---float-) | ينشئ مثيلًا جديدًا من الفئة `CurveShape`. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---float-boolean-) | ينشئ مثيلًا جديدًا من الفئة `CurveShape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTension()](#getTension--) | يحصل أو يضبط توتر المنحنى. |
| [setTension(float value)](#setTension-float-) | يحصل أو يضبط توتر المنحنى. |
| [getBounds()](#getBounds--) | يحصل على حدود الكائن. |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | يحصل على حدود الكائن. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


ينشئ مثيلًا جديدًا من الفئة `CurveShape`.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.imaging.PointF---}
```
public CurveShape(PointF[] points)
```


ينشئ مثيلًا جديدًا من الفئة `CurveShape`. يتم استخدام التوتر الافتراضي بقيمة 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


ينشئ مثيلًا جديدًا من الفئة `CurveShape`. يتم استخدام التوتر الافتراضي بقيمة 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.imaging.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


ينشئ مثيلًا جديدًا من الفئة `CurveShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |
| tension | float | توتر المنحنى. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


ينشئ مثيلًا جديدًا من الفئة `CurveShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |
| tension | float | توتر المنحنى. |
| isClosed | boolean | إذا تم تعيينه إلى `true` فإن المنحنى مغلق. |

### getTension() {#getTension--}
```
public float getTension()
```


يحصل أو يضبط توتر المنحنى.

القيمة: توتر المنحنى.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


يحصل أو يضبط توتر المنحنى.

القيمة: توتر المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

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
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن الآخر. |

**Returns:**
boolean - نتيجة مقارنة المساواة.
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int - رمز التجزئة.
