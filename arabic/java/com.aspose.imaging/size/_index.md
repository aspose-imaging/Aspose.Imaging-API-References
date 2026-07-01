---
title: "الحجم"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل الحجم."
type: docs
weight: 104
url: /ar/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

يمثل الحجم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | ينشئ مثيلاً جديداً من بنية `Aspose.Imaging.Size` من `Aspose.Imaging.Point` المحدد. |
| [Size(int width, int height)](#Size-int-int-) | ينشئ مثيلاً جديداً من بنية `Aspose.Imaging.Size` من الأبعاد المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmpty()](#getEmpty--) | يحصل على مثيل جديد من بنية `Aspose.Imaging.Size` حيث تكون قيم `Aspose.Imaging.Size.Width` و `Aspose.Imaging.Size.Height` مضبوطة على الصفر. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | يحوّل `Aspose.Imaging.Size` المحدد إلى `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | يضيف عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة إلى عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | يطرح عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة من عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | يفحص ما إذا كانت بنيتا `Aspose.Imaging.Size` متساويتين. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | يفحص ما إذا كانت بنيتا `Aspose.Imaging.Size` مختلفتين. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | يحوّل `Aspose.Imaging.Size` المحدد إلى `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | يضيف عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة إلى عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | يحوّل بنية `Aspose.Imaging.SizeF` المحددة إلى بنية `Aspose.Imaging.Size` عن طريق تقريب قيم بنية `Aspose.Imaging.Size` إلى القيم الصحيحة الأعلى التالية. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | يطرح عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة من عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | يحوّل بنية `Aspose.Imaging.SizeF` المحددة إلى بنية `Aspose.Imaging.Size` عن طريق قطع قيم بنية `Aspose.Imaging.SizeF` إلى القيم الصحيحة الأدنى التالية. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | يحوّل بنية `Aspose.Imaging.SizeF` المحددة إلى بنية `Aspose.Imaging.Size` عن طريق تقريب قيم بنية `Aspose.Imaging.SizeF` إلى أقرب قيمة صحيحة. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان `Aspose.Imaging.Size` هذا لديه عرض وارتفاع يساويان 0. |
| [getWidth()](#getWidth--) | يحصل أو يضبط المكوّن الأفقي لهذا `Aspose.Imaging.Size`. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يضبط المكوّن الأفقي لهذا `Aspose.Imaging.Size`. |
| [getHeight()](#getHeight--) | يحصل أو يضبط المكوّن العمودي لهذا `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يضبط المكوّن العمودي لهذا `Aspose.Imaging.Size`. |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان الكائن المحدد هو `Aspose.Imaging.Size` بنفس الأبعاد كما هذا `Aspose.Imaging.Size`. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الهيكل `Aspose.Imaging.Size`. |
| [toString()](#toString--) | ينشئ سلسلة قابلة للقراءة تمثّل هذا `Aspose.Imaging.Size`. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


ينشئ مثيلاً جديداً من بنية `Aspose.Imaging.Size` من `Aspose.Imaging.Point` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Aspose.Imaging.Point` الذي يُستخدم لتهيئة هذا `Aspose.Imaging.Size`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


ينشئ مثيلاً جديداً من بنية `Aspose.Imaging.Size` من الأبعاد المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | مكوّن العرض للـ `Aspose.Imaging.Size` الجديد. |
| height | int | مكوّن الارتفاع للـ `Aspose.Imaging.Size` الجديد. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


يحصل على مثيل جديد من بنية `Aspose.Imaging.Size` حيث تكون قيم `Aspose.Imaging.Size.Width` و `Aspose.Imaging.Size.Height` مضبوطة على الصفر.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


يحوّل `Aspose.Imaging.Size` المحدد إلى `Aspose.Imaging.SizeF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` للتحويل. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


يضيف عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة إلى عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` الأول للإضافة. |
| size2 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` الثاني للإضافة. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


يطرح عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة من عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيسر من عامل الطرح. |
| size2 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيمن من عامل الطرح. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


يفحص ما إذا كانت بنيتا `Aspose.Imaging.Size` متساويتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيسر من عامل المساواة. |
| size2 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيمن من عامل المساواة. |

**Returns:**
منطقي - صحيح إذا كان `size1` و `size2` لهما نفس العرض والارتفاع؛ وإلا، خطأ.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


يفحص ما إذا كانت بنيتا `Aspose.Imaging.Size` مختلفتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيسر من عامل عدم المساواة. |
| size2 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيمن من عامل عدم المساواة. |

**Returns:**
منطقي - صحيح إذا كان `size1` و `size2` يختلفان إما في العرض أو الارتفاع؛ خطأ إذا كانا متساويين.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


يحوّل `Aspose.Imaging.Size` المحدد إلى `Aspose.Imaging.Point`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` للتحويل. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


يضيف عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة إلى عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` الأول للإضافة. |
| size2 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` الثاني للإضافة. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


يحوّل بنية `Aspose.Imaging.SizeF` المحددة إلى بنية `Aspose.Imaging.Size` عن طريق تقريب قيم بنية `Aspose.Imaging.Size` إلى القيم الصحيحة الأعلى التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | الهيكل `Aspose.Imaging.SizeF` للتحويل. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


يطرح عرض وارتفاع بنية `Aspose.Imaging.Size` واحدة من عرض وارتفاع بنية `Aspose.Imaging.Size` أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيسر من عامل الطرح. |
| size2 | [Size](../../com.aspose.imaging/size) | الهيكل `Aspose.Imaging.Size` على الجانب الأيمن من عامل الطرح. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


يحوّل بنية `Aspose.Imaging.SizeF` المحددة إلى بنية `Aspose.Imaging.Size` عن طريق قطع قيم بنية `Aspose.Imaging.SizeF` إلى القيم الصحيحة الأدنى التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | الهيكل `Aspose.Imaging.SizeF` للتحويل. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


يحوّل بنية `Aspose.Imaging.SizeF` المحددة إلى بنية `Aspose.Imaging.Size` عن طريق تقريب قيم بنية `Aspose.Imaging.SizeF` إلى أقرب قيمة صحيحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | الهيكل `Aspose.Imaging.SizeF` للتحويل. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان `Aspose.Imaging.Size` هذا لديه عرض وارتفاع يساويان 0.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يضبط المكوّن الأفقي لهذا `Aspose.Imaging.Size`.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يضبط المكوّن الأفقي لهذا `Aspose.Imaging.Size`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يضبط المكوّن العمودي لهذا `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يضبط المكوّن العمودي لهذا `Aspose.Imaging.Size`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان الكائن المحدد هو `Aspose.Imaging.Size` بنفس الأبعاد كما هذا `Aspose.Imaging.Size`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن `System.Object` للاختبار. |

**Returns:**
منطقي - صحيح إذا كان `obj` هو `Aspose.Imaging.Size` وله نفس العرض والارتفاع كهذا `Aspose.Imaging.Size`؛ وإلا، خطأ.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا الهيكل `Aspose.Imaging.Size`.

**Returns:**
عدد صحيح - قيمة عددية تحدد قيمة تجزئة لهذا الهيكل `Aspose.Imaging.Size`.
### toString() {#toString--}
```
public String toString()
```


ينشئ سلسلة قابلة للقراءة تمثّل هذا `Aspose.Imaging.Size`.

**Returns:**
java.lang.String - سلسلة تمثّل هذا `Aspose.Imaging.Size`.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
