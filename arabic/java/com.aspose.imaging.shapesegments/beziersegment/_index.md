---
title: "BezierSegment"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "مقطع بيزيير الذي ينتقل من نقطة إلى النقطة التالية باستخدام نقطتي تحكم."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

مقطع بيزيير الذي ينتقل من نقطة إلى النقطة التالية باستخدام نقطتي تحكم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | ينشئ مثيلاً جديداً من الفئة `BezierSegment`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | يحصل على نقطة التحكم الأولى لمنحنى بيزير. |
| [getSecondControlPoint()](#getSecondControlPoint--) | يحصل على نقطة التحكم الثانية لمنحنى بيزير. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


ينشئ مثيلاً جديداً من الفئة `BezierSegment`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | نقطة البداية. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | نقطة التحكم الأولى. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | نقطة التحكم الثانية. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | نقطة النهاية. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


يحصل على نقطة التحكم الأولى لمنحنى بيزير.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


يحصل على نقطة التحكم الثانية لمنحنى بيزير.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
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
