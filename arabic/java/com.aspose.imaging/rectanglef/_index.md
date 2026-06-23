---
title: "RectangleF"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل."
type: docs
weight: 94
url: /ar/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | يُنشئ مثيلًا جديدًا لهياكل `com.aspose.imaging.RectangleF` بالموقع والحجم المحددين. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | يُنشئ مثيلًا جديدًا لهياكل `com.aspose.imaging.RectangleF` بالموقع والحجم المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmpty()](#getEmpty--) | يحصل على مثيل جديد لهياكل `com.aspose.imaging.RectangleF` حيث تكون قيم `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Width` و `com.aspose.imaging.RectangleF.Height` مضبوطة على الصفر. |
| [getLocation()](#getLocation--) | يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getSize()](#getSize--) | يحصل أو يعيّن حجم هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | يحصل أو يعيّن حجم هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | يحصل أو يعيّن إحداثي x للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setX(float value)](#setX-float-) | يحصل أو يعيّن إحداثي x للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getY()](#getY--) | يحصل أو يعيّن إحداثي y للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setY(float value)](#setY-float-) | يحصل أو يعيّن إحداثي y للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن عرض هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setWidth(float value)](#setWidth-float-) | يحصل أو يعيّن عرض هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن ارتفاع هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setHeight(float value)](#setHeight-float-) | يحصل أو يعيّن ارتفاع هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getLeft()](#getLeft--) | يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setLeft(float value)](#setLeft-float-) | يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getTop()](#getTop--) | يحصل أو يعيّن إحداثي y للحافة العليا لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setTop(float value)](#setTop-float-) | يحصل أو يعيّن إحداثي y للحافة العليا لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getRight()](#getRight--) | يحصل أو يعيّن إحداثي x الذي هو مجموع `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Width` لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setRight(float value)](#setRight-float-) | يحصل أو يعيّن إحداثي x الذي هو مجموع `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Width` لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [getBottom()](#getBottom--) | يحصل أو يعيّن إحداثي y الذي هو مجموع `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Height` لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [setBottom(float value)](#setBottom-float-) | يحصل أو يعيّن إحداثي y الذي هو مجموع `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Height` لهذه الهياكل `com.aspose.imaging.RectangleF`. |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كانت خاصية `com.aspose.imaging.RectangleF.Width` أو `com.aspose.imaging.RectangleF.Height` لهذه الهياكل `com.aspose.imaging.RectangleF` تساوي الصفر. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | ينشئ `Rectangle` جديدًا من نقطتين محددتين. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | ينشئ ويعيد نسخة موسعة من الهياكل `com.aspose.imaging.RectangleF` المحددة. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | يعيد هياكل `com.aspose.imaging.RectangleF` التي تمثل تقاطع مستطيلين. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | يفحص ما إذا كانت هياكل `com.aspose.imaging.RectangleF` الاثنين لها موقع وحجم متساويين. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | يفحص ما إذا كانت هياكل `com.aspose.imaging.RectangleF` الاثنين تختلف في الموقع أو الحجم. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | ينفّذ العامل \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | ينفّذ العامل /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | يحوّل الهياكل `com.aspose.imaging.Rectangle` المحددة إلى هياكل `com.aspose.imaging.RectangleF`. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | ينشئ هياكل `com.aspose.imaging.RectangleF` مع الزاوية العليا اليسرى والزاوية السفلية اليمنى في المواقع المحددة. |
| [normalize()](#normalize--) | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، والجانب الأيسر أصغر من الجانب الأيمن، والجانب العلوي أصغر من الجانب السفلي. |
| [contains(float x, float y)](#contains-float-float-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه الهياكل `com.aspose.imaging.RectangleF`. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها `rect` مضمونة بالكامل داخل بنية `com.aspose.imaging.RectangleF` هذه. |
| [inflate(float x, float y)](#inflate-float-float-) | يوسع بنية `com.aspose.imaging.RectangleF` هذه بالمقدار المحدد. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | يوسع `com.aspose.imaging.RectangleF` هذه بالمقدار المحدد. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | يستبدل بنية `com.aspose.imaging.RectangleF` هذه بالتقاطع بين نفسها والبنية `com.aspose.imaging.RectangleF` المحددة. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(float x, float y)](#offset-float-float-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان `obj` هو `com.aspose.imaging.RectangleF` بنفس الموقع والحجم لهذا `com.aspose.imaging.RectangleF`. |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لهذه بنية `com.aspose.imaging.RectangleF`. |
| [toString()](#toString--) | يحوّل خصائص `com.aspose.imaging.RectangleF` هذه إلى سلسلة قابلة للقراءة البشرية. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


يُنشئ مثيلًا جديدًا لهياكل `com.aspose.imaging.RectangleF` بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل. |
| width | float | عرض المستطيل. |
| height | float | ارتفاع المستطيل. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


يُنشئ مثيلًا جديدًا لهياكل `com.aspose.imaging.RectangleF` بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | كائن `com.aspose.imaging.PointF` يمثل الزاوية العلوية اليسرى للمنطقة المستطيلة. |
| size | [SizeF](../../com.aspose.imaging/sizef) | كائن `com.aspose.imaging.SizeF` يمثل عرض وارتفاع المنطقة المستطيلة. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


يحصل على مثيل جديد لهياكل `com.aspose.imaging.RectangleF` حيث تكون قيم `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Width` و `com.aspose.imaging.RectangleF.Height` مضبوطة على الصفر.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


يحصل أو يعيّن حجم هذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


يحصل أو يعيّن حجم هذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


يحصل أو يعيّن إحداثي x للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - الإحداثي السيني للزاوية العلوية اليسرى لهذه بنية `com.aspose.imaging.RectangleF`.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


يحصل أو يعيّن إحداثي x للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public float getY()
```


يحصل أو يعيّن إحداثي y للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - الإحداثي الصادي للزاوية العلوية اليسرى لهذه بنية `com.aspose.imaging.RectangleF`.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


يحصل أو يعيّن إحداثي y للزاوية العليا اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


يحصل أو يعيّن عرض هذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - عرض هذه بنية `com.aspose.imaging.RectangleF`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


يحصل أو يعيّن عرض هذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


يحصل أو يعيّن ارتفاع هذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - ارتفاع هذه بنية `com.aspose.imaging.RectangleF`.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


يحصل أو يعيّن ارتفاع هذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - الإحداثي السيني للحافة اليسرى لهذه بنية `com.aspose.imaging.RectangleF`.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


يحصل أو يعيّن إحداثي y للحافة العليا لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - الإحداثي الصادي للحافة العليا لهذه بنية `com.aspose.imaging.RectangleF`.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


يحصل أو يعيّن إحداثي y للحافة العليا لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


يحصل أو يعيّن إحداثي x الذي هو مجموع `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Width` لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - إحداثي x الذي هو مجموع `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Width` لهذا الهيكل `com.aspose.imaging.RectangleF`.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


يحصل أو يعيّن إحداثي x الذي هو مجموع `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Width` لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


يحصل أو يعيّن إحداثي y الذي هو مجموع `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Height` لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Returns:**
float - إحداثي y الذي هو مجموع `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Height` لهذا الهيكل `com.aspose.imaging.RectangleF`.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


يحصل أو يعيّن إحداثي y الذي هو مجموع `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Height` لهذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كانت خاصية `com.aspose.imaging.RectangleF.Width` أو `com.aspose.imaging.RectangleF.Height` لهذه الهياكل `com.aspose.imaging.RectangleF` تساوي الصفر.

**Returns:**
boolean - تُعيد هذه الخاصية true إذا كان خاصية `com.aspose.imaging.RectangleF.Width` أو `com.aspose.imaging.RectangleF.Height` لهذا `com.aspose.imaging.RectangleF` تساوي صفرًا؛ وإلا false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


ينشئ `Rectangle` جديدًا من نقطتين محددتين. سيكون رُؤوس الـ `Rectangle` المُنشأ مساوية للنقطتين `point1` و `point2` الممررتين. عادةً ما تكون هذه الرؤوس هي الرؤوس المتقابلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | النقطة `Point` الأولى للمستطيل الجديد. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | النقطة `Point` الثانية للمستطيل الجديد. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


ينشئ ويُعيد نسخة مُوسعة من الهيكل `com.aspose.imaging.RectangleF` المحدد. تُوسَّع النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` الذي سيُنسخ. هذا المستطيل غير معدل. |
| x | float | المقدار لتوسيع نسخة المستطيل أفقياً. |
| y | float | المقدار لتوسيع نسخة المستطيل عمودياً. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


يعيد هيكل `com.aspose.imaging.RectangleF` يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع `com.aspose.imaging.RectangleF` فارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل الأول للتقاطع. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل الثاني للتقاطع. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل الأول للاتحاد. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل الثاني للاتحاد. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


يفحص ما إذا كانت هياكل `com.aspose.imaging.RectangleF` الاثنين لها موقع وحجم متساويين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` الموجود على يسار عامل المساواة. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` الموجود على يمين عامل المساواة. |

**Returns:**
boolean - يُعيد هذا العامل true إذا كان الهيكلان `com.aspose.imaging.RectangleF` المحددان يمتلكان خصائص `com.aspose.imaging.RectangleF.X` و `com.aspose.imaging.RectangleF.Y` و `com.aspose.imaging.RectangleF.Width` و `com.aspose.imaging.RectangleF.Height` متساوية.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


يفحص ما إذا كانت هياكل `com.aspose.imaging.RectangleF` الاثنين تختلف في الموقع أو الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` الموجود على يسار عامل عدم المساواة. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` الموجود على يمين عامل عدم المساواة. |

**Returns:**
boolean - يُعيد هذا العامل true إذا كان أي من خصائص `com.aspose.imaging.RectangleF.X` أو `com.aspose.imaging.RectangleF.Y` أو `com.aspose.imaging.RectangleF.Width` أو `com.aspose.imaging.RectangleF.Height` للهيكلين `com.aspose.imaging.RectangleF` غير متساوية؛ وإلا false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


ينفّذ العامل \*.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل. |
| المضاعف | float | المضاعف. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


ينفّذ العامل /.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل. |
| القاسم | float | القاسم. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


يحوّل الهياكل `com.aspose.imaging.Rectangle` المحددة إلى هياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الهيكل `com.aspose.imaging.Rectangle` للتحويل. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


ينشئ هياكل `com.aspose.imaging.RectangleF` مع الزاوية العليا اليسرى والزاوية السفلية اليمنى في المواقع المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | float | الإحداثي السيني للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| أعلى | float | الإحداثي الصادي للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| يمين | float | الإحداثي السيني للزاوية السفلية اليمنى للمنطقة المستطيلة. |
| أسفل | float | الإحداثي الصادي للزاوية السفلية اليمنى للمنطقة المستطيلة. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، والجانب الأيسر أصغر من الجانب الأيمن، والجانب العلوي أصغر من الجانب السفلي.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كانت النقطة المحددة بـ `x` و `y` موجودة داخل هيكل `com.aspose.imaging.RectangleF` هذا؛ وإلا false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه الهياكل `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للاختبار. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كانت النقطة الممثلة بواسطة معامل `point` موجودة داخل هيكل `com.aspose.imaging.RectangleF` هذا؛ وإلا false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها `rect` مضمونة بالكامل داخل بنية `com.aspose.imaging.RectangleF` هذه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | الـ `com.aspose.imaging.RectangleF` للاختبار. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل المنطقة المستطيلة الممثلة بهذا `com.aspose.imaging.RectangleF`؛ وإلا false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


يوسع بنية `com.aspose.imaging.RectangleF` هذه بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الكمية لتوسيع هذا الهيكل `com.aspose.imaging.RectangleF` أفقياً. |
| y | float | الكمية لتوسيع هذا الهيكل `com.aspose.imaging.RectangleF` عمودياً. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


يوسع `com.aspose.imaging.RectangleF` هذه بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | الكمية لتوسيع هذا المستطيل. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


يستبدل بنية `com.aspose.imaging.RectangleF` هذه بالتقاطع بين نفسها والبنية `com.aspose.imaging.RectangleF` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل للتقاطع. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل للاختبار. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كان هناك أي تقاطع.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | الكمية لإزاحة الموقع. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الكمية لإزاحة الموقع أفقياً. |
| y | float | الكمية لإزاحة الموقع عمودياً. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان `obj` هو `com.aspose.imaging.RectangleF` بنفس الموقع والحجم لهذا `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن `System.Object` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كان `obj` هو `com.aspose.imaging.RectangleF` وكانت خصائص X و Y و Width و Height مساوية للخصائص المقابلة لهذا `com.aspose.imaging.RectangleF`؛ وإلا، false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على رمز التجزئة لهذه بنية `com.aspose.imaging.RectangleF`.

**Returns:**
int - رمز التجزئة لهذا `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


يحوّل خصائص `com.aspose.imaging.RectangleF` هذه إلى سلسلة قابلة للقراءة البشرية.

**Returns:**
java.lang.String - سلسلة تحتوي على الموضع والعرض والارتفاع لهذا الهيكل `com.aspose.imaging.RectangleF`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
