---
title: "PointF"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل زوجًا مرتبًا من إحداثيات x و y عائمة يحدد نقطة في مستوى ثنائي الأبعاد."
type: docs
weight: 87
url: /ar/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

يمثل زوجًا مرتبًا من إحداثيات x و y عائمة يحدد نقطة في مستوى ثنائي الأبعاد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | يُنشئ مثيلاً جديدًا من البنية `com.aspose.imaging.PointF` بالإحداثيات المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmpty()](#getEmpty--) | يحصل على مثيل جديد من البنية `com.aspose.imaging.PointF` التي تكون قيم `com.aspose.imaging.PointF.X` و `com.aspose.imaging.PointF.Y` فيها صفرًا. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | ينقل `com.aspose.imaging.PointF` بمقدار `com.aspose.imaging.Size` المحدد. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | ينقل `com.aspose.imaging.PointF` بالسالب من `com.aspose.imaging.Size` المحدد. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | ينقل `com.aspose.imaging.PointF` بالمقدار المحدد من `com.aspose.imaging.SizeF`. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | ينقل `com.aspose.imaging.PointF` بالسالب من `com.aspose.imaging.SizeF` المحدد. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | يقارن بين هيكلي `com.aspose.imaging.PointF`. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | يحدد ما إذا كانت إحداثيات النقاط المحددة غير متساوية. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | ينقل `com.aspose.imaging.PointF` المحدد بالمقدار المحدد من `com.aspose.imaging.Size`. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | ينقل `com.aspose.imaging.PointF` بالسالب من الحجم المحدد. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | ينقل `com.aspose.imaging.PointF` المحدد بالمقدار المحدد من `com.aspose.imaging.SizeF`. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | ينقل `com.aspose.imaging.PointF` بالسالب من الحجم المحدد. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان هذا `com.aspose.imaging.PointF` فارغًا. |
| [getX()](#getX--) | يحصل أو يعيّن الإحداثي السيني لهذا `com.aspose.imaging.PointF`. |
| [setX(float value)](#setX-float-) | يحصل أو يعيّن الإحداثي السيني لهذا `com.aspose.imaging.PointF`. |
| [getY()](#getY--) | يحصل أو يعيّن الإحداثي الصادي لهذا `com.aspose.imaging.PointF`. |
| [setY(float value)](#setY-float-) | يحصل أو يعيّن الإحداثي الصادي لهذا `com.aspose.imaging.PointF`. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان هذا `com.aspose.imaging.PointF` يحتوي على نفس الإحداثيات كما في `System.Object` المحدد. |
| [hashCode()](#hashCode--) | يعيد رمز تجزئة لهذه البنية `com.aspose.imaging.PointF`. |
| [toString()](#toString--) | يقوم بتحويل هذا `com.aspose.imaging.PointF` إلى سلسلة قابلة للقراءة البشرية. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


يُنشئ مثيلاً جديدًا من البنية `com.aspose.imaging.PointF` بالإحداثيات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الموضع الأفقي للنقطة. |
| y | float | الموضع العمودي للنقطة. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


يحصل على مثيل جديد من البنية `com.aspose.imaging.PointF` التي تكون قيم `com.aspose.imaging.PointF.X` و `com.aspose.imaging.PointF.Y` فيها صفرًا.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


ينقل `com.aspose.imaging.PointF` بمقدار `com.aspose.imaging.Size` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للترجمة. |
| size | [Size](../../com.aspose.imaging/size) | `com.aspose.imaging.Size` يحدد زوج الأرقام لإضافتها إلى إحداثيات `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


ينقل `com.aspose.imaging.PointF` بالسالب من `com.aspose.imaging.Size` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` للترجمة. |
| size | [Size](../../com.aspose.imaging/size) | `com.aspose.imaging.Size` يحدد الأرقام لطرحها من إحداثيات x و y للـ `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


ينقل `com.aspose.imaging.PointF` بالمقدار المحدد من `com.aspose.imaging.SizeF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للترجمة. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `com.aspose.imaging.SizeF` يحدد الأرقام لإضافتها إلى إحداثيات x و y للـ `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


ينقل `com.aspose.imaging.PointF` بالسالب من `com.aspose.imaging.SizeF` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للترجمة. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `com.aspose.imaging.SizeF` يحدد الأرقام لطرحها من إحداثيات `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


يقارن بين هيكلي `com.aspose.imaging.PointF` اثنين. النتيجة تحدد ما إذا كانت قيم خصائص `com.aspose.imaging.PointF.X` و `com.aspose.imaging.PointF.Y` للهيكلين `com.aspose.imaging.PointF` متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الأول للمقارنة. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الثاني للمقارنة. |

**Returns:**
منطقي - صحيح إذا كانت قيم `com.aspose.imaging.PointF.X` و `com.aspose.imaging.PointF.Y` للهيكلين الأول والثاني `com.aspose.imaging.PointF` متساوية؛ وإلا، خطأ.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


يحدد ما إذا كانت إحداثيات النقاط المحددة غير متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الأول للمقارنة. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الثاني للمقارنة. |

**Returns:**
منطقي - صحيح للإشارة إلى أن قيم `com.aspose.imaging.PointF.X` و `com.aspose.imaging.PointF.Y` لـ `point1` و `point2` غير متساوية؛ وإلا، خطأ.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


ينقل `com.aspose.imaging.PointF` المحدد بالمقدار المحدد من `com.aspose.imaging.Size`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للترجمة. |
| size | [Size](../../com.aspose.imaging/size) | `com.aspose.imaging.Size` يحدد الأرقام لإضافتها إلى إحداثيات `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


ينقل `com.aspose.imaging.PointF` بالسالب من الحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للترجمة. |
| size | [Size](../../com.aspose.imaging/size) | `com.aspose.imaging.Size` يحدد الأرقام لطرحها من إحداثيات `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


ينقل `com.aspose.imaging.PointF` المحدد بالمقدار المحدد من `com.aspose.imaging.SizeF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للترجمة. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `com.aspose.imaging.SizeF` يحدد الأرقام لإضافتها إلى إحداثيات `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


ينقل `com.aspose.imaging.PointF` بالسالب من الحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` للترجمة. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `com.aspose.imaging.SizeF` يحدد الأرقام لطرحها من إحداثيات `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `com.aspose.imaging.PointF` فارغًا.

**Returns:**
منطقي - صحيح إذا كان كل من `com.aspose.imaging.PointF.X` و `com.aspose.imaging.PointF.Y` يساوي 0؛ وإلا، خطأ.
### getX() {#getX--}
```
public float getX()
```


يحصل أو يعيّن الإحداثي السيني لهذا `com.aspose.imaging.PointF`.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


يحصل أو يعيّن الإحداثي السيني لهذا `com.aspose.imaging.PointF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public float getY()
```


يحصل أو يعيّن الإحداثي الصادي لهذا `com.aspose.imaging.PointF`.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


يحصل أو يعيّن الإحداثي الصادي لهذا `com.aspose.imaging.PointF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان هذا `com.aspose.imaging.PointF` يحتوي على نفس الإحداثيات كما في `System.Object` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن `System.Object` للاختبار. |

**Returns:**
منطقي - تُعيد هذه الطريقة صحيح إذا كان `obj` من نوع `com.aspose.imaging.PointF` وله نفس الإحداثيات مثل هذا `com.aspose.imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة لهذه البنية `com.aspose.imaging.PointF`.

**Returns:**
عدد صحيح - قيمة عددية تحدد قيمة تجزئة لهذا الهيكل `com.aspose.imaging.PointF`.
### toString() {#toString--}
```
public String toString()
```


يقوم بتحويل هذا `com.aspose.imaging.PointF` إلى سلسلة قابلة للقراءة البشرية.

**Returns:**
java.lang.String - سلسلة تمثل هذا `com.aspose.imaging.PointF`.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
