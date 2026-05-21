---
title: "RectangleProjectedShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل شكلاً يتم إسقاطه على مستطيل موجه إلى اتجاه معين."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

يمثل شكلاً يتم إسقاطه على مستطيل موجه بزاوية معينة. يتم تحديده بأربع نقاط يمكن تدويرها في الفضاء مع الحفاظ على طول الحواف نفسه و90 درجة بين الحواف المتجاورة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | يحصل على النقطة اليسرى العليا للمستطيل. |
| [getRightTop()](#getRightTop--) | يحصل على النقطة اليمنى العليا للمستطيل. |
| [getLeftBottom()](#getLeftBottom--) | يحصل على النقطة اليسرى السفلى للمستطيل. |
| [getRightBottom()](#getRightBottom--) | يحصل على النقطة اليمنى السفلى للمستطيل. |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getBounds()](#getBounds--) | يحصل على حدود الكائن. |
| [getRectangleWidth()](#getRectangleWidth--) | يحصل على عرض المستطيل. |
| [getRectangleHeight()](#getRectangleHeight--) | يحصل على ارتفاع المستطيل. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | يحصل على حدود الكائن. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


يحصل على النقطة اليسرى العليا للمستطيل.

القيمة: النقطة اليسرى العليا للمستطيل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


يحصل على النقطة اليمنى العليا للمستطيل.

القيمة: النقطة اليمنى العليا للمستطيل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


يحصل على النقطة اليسرى السفلى للمستطيل.

القيمة: النقطة اليسرى السفلى للمستطيل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


يحصل على النقطة اليمنى السفلى للمستطيل.

القيمة: النقطة اليمنى السفلى للمستطيل.

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

القيمة: `True` إذا كان الشكل يحتوي على مقاطع؛ وإلا `false`.

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


يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | ال `Object` للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الـ `Object` المحدد يساوي هذه الحالة؛ وإلا `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
