---
title: "Point"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل زوجًا مرتبًا من إحداثيات x و y صحيحة يحدد نقطة في مستوى ثنائي الأبعاد."
type: docs
weight: 86
url: /ar/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

يمثل زوجًا مرتبًا من إحداثيات x و y صحيحة يحدد نقطة في مستوى ثنائي الأبعاد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | ينشئ نسخة جديدة من بنية `Aspose.Imaging.Point` مع الإحداثيات المحددة. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | ينشئ نسخة جديدة من بنية `Aspose.Imaging.Point` من بنية `Aspose.Imaging.Size`. |
| [Point(int dw)](#Point-int-) | ينشئ نسخة جديدة من بنية `Aspose.Imaging.Point` باستخدام إحداثيات محددة بقيمة عدد صحيح. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmpty()](#getEmpty--) | يحصل على نسخة جديدة من بنية `Aspose.Imaging.Point` التي تحتوي على قيم `Aspose.Imaging.Point.X` و `Aspose.Imaging.Point.Y` مضبوطة على الصفر. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | يضيف `Aspose.Imaging.Size` المحدد إلى `Aspose.Imaging.Point` المحدد. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | يرجع نتيجة طرح `Aspose.Imaging.Size` المحدد من `Aspose.Imaging.Point` المحدد. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | يحوّل `Aspose.Imaging.PointF` المحدد إلى `Aspose.Imaging.Point` عن طريق تقريب قيم `Aspose.Imaging.PointF` إلى القيم الصحيحة الأعلى. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | يحوّل `Aspose.Imaging.PointF` المحدد إلى كائن `Aspose.Imaging.Point` عن طريق تقريب القيم إلى أقرب عدد صحيح. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | يحوّل `Aspose.Imaging.PointF` المحدد إلى `Aspose.Imaging.Point` عن طريق قطع قيم `Aspose.Imaging.Point`. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | ينقل `Aspose.Imaging.Point` بمقدار `Aspose.Imaging.Size` المعطى. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | ينقل `Aspose.Imaging.Point` بالسالب من `Aspose.Imaging.Size` المعطى. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | يقارن كائنين من نوع `Aspose.Imaging.Point`. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | يقارن كائنين من نوع `Aspose.Imaging.Point`. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | يحوّل بنية `Aspose.Imaging.Point` المحددة إلى بنية `Aspose.Imaging.Size`. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | يحوّل بنية `Point` المحددة إلى بنية `PointF`. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | يفكّ بنية كائن Point المعبّأ في كائن طويل إلى قيم X و Y من نوع int منفصلة. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان `Aspose.Imaging.Point` هذا فارغًا. |
| [getX()](#getX--) | يحصل أو يعيّن الإحداثي x لهذا `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | يحصل أو يعيّن الإحداثي x لهذا `Aspose.Imaging.Point`. |
| [getY()](#getY--) | يحصل أو يعيّن الإحداثي y لهذا `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | يحصل أو يعيّن الإحداثي y لهذا `Aspose.Imaging.Point`. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | ينقل هذا `Aspose.Imaging.Point` بمقدار `Aspose.Imaging.Point` المحدد. |
| [offset(int dx, int dy)](#offset-int-int-) | ينقل هذا `Aspose.Imaging.Point` بالمقدار المحدد. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `Aspose.Imaging.Point` هذا يحتوي على نفس الإحداثيات مثل `System.Object` المحدد. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا `Aspose.Imaging.Point`. |
| [toLong()](#toLong--) | يحوّل هذا Point إلى قيمة طويلة واحدة، تحتوي على إحداثيات X و Y في البتات العليا والسفلى. |
| [toString()](#toString--) | يحوّل هذا `Aspose.Imaging.Point` إلى سلسلة قابلة للقراءة من قبل الإنسان. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


ينشئ نسخة جديدة من بنية `Aspose.Imaging.Point` مع الإحداثيات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الموضع الأفقي للنقطة. |
| ص | int | الموضع الرأسي للنقطة. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


ينشئ نسخة جديدة من بنية `Aspose.Imaging.Point` من بنية `Aspose.Imaging.Size`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | يحتوي على إحداثيات النقطة الجديدة. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


ينشئ نسخة جديدة من بنية `Aspose.Imaging.Point` باستخدام إحداثيات محددة بقيمة عدد صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dw | int | عدد صحيح 32 بت يحدد إحداثيات النقطة الجديدة. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


يحصل على نسخة جديدة من بنية `Aspose.Imaging.Point` التي تحتوي على قيم `Aspose.Imaging.Point.X` و `Aspose.Imaging.Point.Y` مضبوطة على الصفر.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


يضيف `Aspose.Imaging.Size` المحدد إلى `Aspose.Imaging.Point` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Aspose.Imaging.Point` للإضافة إليه. |
| size | [Size](../../com.aspose.imaging/size) | الـ `Aspose.Imaging.Size` للإضافة إلى `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


يرجع نتيجة طرح `Aspose.Imaging.Size` المحدد من `Aspose.Imaging.Point` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Aspose.Imaging.Point` ليتم طرحه من. |
| size | [Size](../../com.aspose.imaging/size) | الـ `Aspose.Imaging.Size` لطرحها من `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


يحوّل `Aspose.Imaging.PointF` المحدد إلى `Aspose.Imaging.Point` عن طريق تقريب قيم `Aspose.Imaging.PointF` إلى القيم الصحيحة الأعلى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `Aspose.Imaging.PointF` للتحويل. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


يحوّل `Aspose.Imaging.PointF` المحدد إلى كائن `Aspose.Imaging.Point` عن طريق تقريب القيم إلى أقرب عدد صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `Aspose.Imaging.PointF` للتحويل. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


يحوّل `Aspose.Imaging.PointF` المحدد إلى `Aspose.Imaging.Point` عن طريق قطع قيم `Aspose.Imaging.Point`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `Aspose.Imaging.PointF` للتحويل. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


ينقل `Aspose.Imaging.Point` بمقدار `Aspose.Imaging.Size` المعطى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Aspose.Imaging.Point` للتحويل. |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` يحدد زوج الأرقام لإضافتها إلى إحداثيات `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


ينقل `Aspose.Imaging.Point` بالسالب من `Aspose.Imaging.Size` المعطى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Aspose.Imaging.Point` للتحويل. |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` يحدد زوج الأرقام لطرحها من إحداثيات `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


يقارن كائنين من نوع `Aspose.Imaging.Point`. النتيجة تحدد ما إذا كانت قيم خصائص `Aspose.Imaging.Point.X` و `Aspose.Imaging.Point.Y` لكائنين `Aspose.Imaging.Point` متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` الأول للمقارنة. |
| point2 | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` الثاني للمقارنة. |

**Returns:**
منطقي - صحيح إذا كانت قيم `Aspose.Imaging.Point.X` و `Aspose.Imaging.Point.Y` لـ `point1` و `point2` متساوية؛ وإلا، خاطئ.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


يقارن كائنين من نوع `Aspose.Imaging.Point`. النتيجة تحدد ما إذا كانت قيم خصائص `Aspose.Imaging.Point.X` أو `Aspose.Imaging.Point.Y` لكائنين `Aspose.Imaging.Point` غير متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` الأول للمقارنة. |
| point2 | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` الثاني للمقارنة. |

**Returns:**
منطقي - صحيح إذا اختلفت قيم إما خصائص `Aspose.Imaging.Point.X` أو خصائص `Aspose.Imaging.Point.Y` لـ `point1` و `point2`؛ وإلا، خاطئ.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


يحوّل بنية `Aspose.Imaging.Point` المحددة إلى بنية `Aspose.Imaging.Size`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Aspose.Imaging.Point` للتحويل. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


يحوّل بنية `Point` المحددة إلى بنية `PointF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Point` للتحويل. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


يفكّ بنية كائن Point المعبّأ في كائن طويل إلى قيم X و Y من نوع int منفصلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| packedPoint | long | كائن Point المعبأ في قيمة طويلة واحدة. |
| س | int[] | القيمة المستخرجة من X للنقطة المعبأة. |
| ص | int[] | القيمة المستخرجة من Y للنقطة المعبأة. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان `Aspose.Imaging.Point` هذا فارغًا.

**Returns:**
منطقي - صحيح إذا كان كل من `Aspose.Imaging.Point.X` و `Aspose.Imaging.Point.Y` يساوي 0؛ وإلا، خاطئ.
### getX() {#getX--}
```
public int getX()
```


يحصل أو يعيّن الإحداثي x لهذا `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


يحصل أو يعيّن الإحداثي x لهذا `Aspose.Imaging.Point`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getY() {#getY--}
```
public int getY()
```


يحصل أو يعيّن الإحداثي y لهذا `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


يحصل أو يعيّن الإحداثي y لهذا `Aspose.Imaging.Point`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


ينقل هذا `Aspose.Imaging.Point` بمقدار `Aspose.Imaging.Point` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `Aspose.Imaging.Point` المستخدم لإزاحة هذا `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


ينقل هذا `Aspose.Imaging.Point` بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | int | القيمة لإزاحة إحداثي x. |
| dy | int | القيمة لإزاحة إحداثي y. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `Aspose.Imaging.Point` هذا يحتوي على نفس الإحداثيات مثل `System.Object` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ `System.Object` للاختبار. |

**Returns:**
منطقي - صحيح إذا كان `obj` من نوع `Aspose.Imaging.Point` وله نفس الإحداثيات مثل هذا `Aspose.Imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا `Aspose.Imaging.Point`.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### toLong() {#toLong--}
```
public final long toLong()
```


يحوّل هذا Point إلى قيمة طويلة واحدة، تحتوي على إحداثيات X و Y في البتات العليا والسفلى.

**Returns:**
طويل - كائن Point المعبأ في قيمة طويلة واحدة.
### toString() {#toString--}
```
public String toString()
```


يحوّل هذا `Aspose.Imaging.Point` إلى سلسلة قابلة للقراءة من قبل الإنسان.

**Returns:**
java.lang.String - `System.String` يمثل هذا المثيل.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
