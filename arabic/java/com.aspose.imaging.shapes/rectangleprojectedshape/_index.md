---
title: "RectangleProjectedShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل شكلاً يُسقط على مستطيل موجه إلى اتجاه معين."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

يمثل شكلاً يتم إسقاطه على مستطيل موجه إلى اتجاه معين. يُحدد بأربع نقاط يمكن تدويرها في الفضاء مع الحفاظ على نفس طول الحواف و 90 درجة بين الحواف المتجاورة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | يحصل على نقطة الزاوية العليا اليسرى للمستطيل. |
| [getRightTop()](#getRightTop--) | يحصل على نقطة الزاوية العليا اليمنى للمستطيل. |
| [getLeftBottom()](#getLeftBottom--) | يحصل على نقطة الزاوية السفلية اليسرى للمستطيل. |
| [getRightBottom()](#getRightBottom--) | يحصل على نقطة الزاوية السفلية اليمنى للمستطيل. |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getBounds()](#getBounds--) | يحصل على حدود الكائن. |
| [getRectangleWidth()](#getRectangleWidth--) | يحصل على عرض المستطيل. |
| [getRectangleHeight()](#getRectangleHeight--) | يحصل على ارتفاع المستطيل. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | يحصل على حدود الكائن. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


يحصل على نقطة الزاوية العليا اليسرى للمستطيل.

القيمة: نقطة الزاوية العليا اليسرى للمستطيل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


يحصل على نقطة الزاوية العليا اليمنى للمستطيل.

القيمة: نقطة الزاوية العليا اليمنى للمستطيل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


يحصل على نقطة الزاوية السفلية اليسرى للمستطيل.

القيمة: نقطة الزاوية السفلية اليسرى للمستطيل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


يحصل على نقطة الزاوية السفلية اليمنى للمستطيل.

القيمة: نقطة الزاوية السفلية اليمنى للمستطيل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


يحصل على مركز الشكل.

القيمة: مركز الشكل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


يحصل على حدود الكائن.

القيمة: حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


يحصل على عرض المستطيل.

القيمة: عرض المستطيل.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


يحصل على ارتفاع المستطيل.

القيمة: ارتفاع المستطيل.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع.

القيمة: `True` إذا كان الشكل يحتوي على مقاطع؛ وإلا، `false`.

**Returns:**
boolean
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
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | سيتم حساب المصفوفة التي سيتم تطبيقها قبل الحدود. |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم المستخدم للكائن. يمكن أن يؤثر هذا على حجم حدود الكائن. |

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
| transform | [Matrix](../../com.aspose.imaging/matrix) | التحويل الذي سيتم تطبيقه. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن `Object` للمقارنة مع هذه المثيلة. |

**Returns:**
منطقية - `true` إذا كان الـ `Object` المحدد مساويًا لهذه المثيلة؛ وإلا `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - قيمة تجزئة (hash code) لهذا الكائن، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
