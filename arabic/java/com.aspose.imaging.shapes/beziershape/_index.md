---
title: "BezierShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل منحنى بيزيير."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

يمثل منحنى بيزيير.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BezierShape()](#BezierShape--) | ينشئ مثيلاً جديداً من الفئة `BezierShape`. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | ينشئ مثيلاً جديداً من الفئة `BezierShape`. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | ينشئ مثيلاً جديداً من الفئة `BezierShape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل على حدود الكائن. |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [getEndPoint()](#getEndPoint--) | يحصل على نقطة نهاية الشكل. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


ينشئ مثيلاً جديداً من الفئة `BezierShape`.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


ينشئ مثيلاً جديداً من الفئة `BezierShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


ينشئ مثيلاً جديداً من الفئة `BezierShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة النقاط. |
| isClosed | boolean | إذا تم تعيينه إلى `true` فإن منحنى البيزير مغلق. |

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

القيمة: `True` إذا كان الشكل يحتوي على مقاطع؛ وإلا، `false`.

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


يحصل على نقطة نهاية الشكل.

القيمة: نقطة نهاية الشكل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | سيتم حساب المصفوفة التي سيتم تطبيقها قبل الحدود. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
