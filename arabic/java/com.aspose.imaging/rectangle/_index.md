---
title: "مستطيل"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم مستطيل."
type: docs
weight: 93
url: /ar/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم مستطيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | يُنشئ نسخة جديدة من هيكل `com.aspose.imaging.Rectangle` بالموقع والحجم المحددين. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | يُنشئ نسخة جديدة من هيكل `com.aspose.imaging.Rectangle` بالموقع والحجم المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmpty()](#getEmpty--) | يحصل على نسخة جديدة من هيكل `com.aspose.imaging.Rectangle` التي تكون قيم `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Width` و `com.aspose.imaging.Rectangle.Height` فيها صفر. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | ينشئ `Rectangle` جديدًا من نقطتين محددتين. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | يحوّل الهيكل المحدد `com.aspose.imaging.RectangleF` إلى هيكل `com.aspose.imaging.Rectangle` عن طريق تقريب قيم `com.aspose.imaging.RectangleF` إلى أعلى عدد صحيح. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | يحوّل الـ `com.aspose.imaging.RectangleF` المحدد إلى `com.aspose.imaging.Rectangle` بقطع قيم `com.aspose.imaging.RectangleF`. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | يقوم بتحويل الـ `com.aspose.imaging.RectangleF` المحدد إلى `com.aspose.imaging.Rectangle` عن طريق تقريب قيم الـ `com.aspose.imaging.RectangleF` إلى أقرب قيم صحيحة. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | ينشئ ويعيد نسخة موسعة من بنية الـ `com.aspose.imaging.Rectangle` المحددة. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | يعيد بنية `com.aspose.imaging.Rectangle` ثالثة تمثل تقاطع بنيتين `com.aspose.imaging.Rectangle` أخريين. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | يحصل على بنية `com.aspose.imaging.Rectangle` تحتوي على اتحاد بنيتين `com.aspose.imaging.Rectangle`. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | يفحص ما إذا كانت بنيتان `com.aspose.imaging.Rectangle` لهما نفس الموقع والحجم. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | يفحص ما إذا كانت بنيتان `com.aspose.imaging.Rectangle` تختلفان في الموقع أو الحجم. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | ينشئ بنية `com.aspose.imaging.Rectangle` بالمواقع المحددة للحواف. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | يحصل أو يضبط إحداثيات الزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | يحصل أو يضبط إحداثيات الزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [getSize()](#getSize--) | يحصل أو يضبط حجم هذا الـ `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | يحصل أو يضبط حجم هذا الـ `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | يحصل أو يضبط الإحداثي السيني للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [setX(int value)](#setX-int-) | يحصل أو يضبط الإحداثي السيني للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [getY()](#getY--) | يحصل أو يضبط الإحداثي الصادي للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [setY(int value)](#setY-int-) | يحصل أو يضبط الإحداثي الصادي للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [getWidth()](#getWidth--) | يحصل على عرض هذه البنية `com.aspose.imaging.Rectangle`. |
| [setWidth(int value)](#setWidth-int-) | يضبط عرض هذه البنية `com.aspose.imaging.Rectangle`. |
| [getHeight()](#getHeight--) | يحصل أو يضبط ارتفاع هذه البنية `com.aspose.imaging.Rectangle`. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يضبط ارتفاع هذه البنية `com.aspose.imaging.Rectangle`. |
| [getLeft()](#getLeft--) | يحصل أو يضبط الإحداثي السيني للحافة اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [setLeft(int value)](#setLeft-int-) | يحصل أو يضبط الإحداثي السيني للحافة اليسرى لهذه البنية `com.aspose.imaging.Rectangle`. |
| [getTop()](#getTop--) | يحصل أو يضبط الإحداثي الصادي للحافة العليا لهذه البنية `com.aspose.imaging.Rectangle`. |
| [setTop(int value)](#setTop-int-) | يحصل أو يضبط الإحداثي الصادي للحافة العليا لهذه البنية `com.aspose.imaging.Rectangle`. |
| [getRight()](#getRight--) | يحصل أو يضبط الإحداثي السيني الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Width` لهذه البنية `com.aspose.imaging.Rectangle`. |
| [setRight(int value)](#setRight-int-) | يحصل أو يضبط الإحداثي السيني الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Width` لهذه البنية `com.aspose.imaging.Rectangle`. |
| [getBottom()](#getBottom--) | يحصل أو يضبط الإحداثي الصادي الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Height` لهذه البنية `com.aspose.imaging.Rectangle`. |
| [setBottom(int value)](#setBottom-int-) | يحصل أو يضبط الإحداثي الصادي الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Height` لهذه البنية `com.aspose.imaging.Rectangle`. |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذه البنية `com.aspose.imaging.Rectangle` تساوي الصفر. |
| [contains(int x, int y)](#contains-int-int-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية `com.aspose.imaging.Rectangle`. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية `com.aspose.imaging.Rectangle`. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | يحدد ما إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل هذه البنية `com.aspose.imaging.Rectangle`. |
| [inflate(int width, int height)](#inflate-int-int-) | يوسع هذه البنية `com.aspose.imaging.Rectangle` بالمقدار المحدد. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | يوسع هذه البنية `com.aspose.imaging.Rectangle` بالمقدار المحدد. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | يستبدل هذه البنية `com.aspose.imaging.Rectangle` بتقاطعها مع الـ `com.aspose.imaging.Rectangle` المحدد. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(int x, int y)](#offset-int-int-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [normalize()](#normalize--) | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والأعلى أصغر من الأسفل. |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان `obj` بنية `com.aspose.imaging.Rectangle` لها نفس الموقع والحجم لهذه البنية `com.aspose.imaging.Rectangle`. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذا الهيكل `com.aspose.imaging.Rectangle`. |
| [toString()](#toString--) | يقوم بتحويل خصائص هذا `com.aspose.imaging.Rectangle` إلى سلسلة قابلة للقراءة البشرية. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


يُنشئ نسخة جديدة من هيكل `com.aspose.imaging.Rectangle` بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل. |
| ص | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل. |
| العرض | int | عرض المستطيل. |
| الارتفاع | int | ارتفاع المستطيل. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


يُنشئ نسخة جديدة من هيكل `com.aspose.imaging.Rectangle` بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | `com.aspose.imaging.Point` الذي يمثل الزاوية العلوية اليسرى للمنطقة المستطيلة. |
| size | [Size](../../com.aspose.imaging/size) | `com.aspose.imaging.Size` الذي يمثل العرض والارتفاع للمنطقة المستطيلة. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


يحصل على نسخة جديدة من هيكل `com.aspose.imaging.Rectangle` التي تكون قيم `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Width` و `com.aspose.imaging.Rectangle.Height` فيها صفر.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


ينشئ `Rectangle` جديدًا من نقطتين محددتين. سيكون العمودان الرأسيان للـ `Rectangle` المُنشأ مساويين للنقطتين `point1` و `point2` الممررتين. عادةً ما تكون هاتان النقطتان رؤوسًا متقابلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | النقطة الأولى `Point` للمستطيل الجديد. |
| point2 | [Point](../../com.aspose.imaging/point) | النقطة الثانية `Point` للمستطيل الجديد. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


يحوّل الهيكل المحدد `com.aspose.imaging.RectangleF` إلى هيكل `com.aspose.imaging.Rectangle` عن طريق تقريب قيم `com.aspose.imaging.RectangleF` إلى أعلى عدد صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | الهيكل `com.aspose.imaging.RectangleF` المراد تحويله. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


يحوّل الـ `com.aspose.imaging.RectangleF` المحدد إلى `com.aspose.imaging.Rectangle` بقطع قيم `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` المراد تحويله. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


يقوم بتحويل الـ `com.aspose.imaging.RectangleF` المحدد إلى `com.aspose.imaging.Rectangle` عن طريق تقريب قيم الـ `com.aspose.imaging.RectangleF` إلى أقرب قيم صحيحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` المراد تحويله. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


ينشئ ويعيد نسخة موسعة من الهيكل `com.aspose.imaging.Rectangle` المحدد. تُوسّع النسخة بالمقدار المحدد. يظل الهيكل الأصلي `com.aspose.imaging.Rectangle` دون تعديل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle` للبدء به. هذا المستطيل غير معدل. |
| س | int | المقدار لتوسيع هذا `com.aspose.imaging.Rectangle` أفقيًا. |
| ص | int | المقدار لتوسيع هذا `com.aspose.imaging.Rectangle` رأسيًا. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


يعيد هيكل `com.aspose.imaging.Rectangle` ثالث يمثل تقاطع هيكلين `com.aspose.imaging.Rectangle` آخرين. إذا لم يكن هناك تقاطع، يتم إرجاع `com.aspose.imaging.Rectangle` فارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الأول للتقاطع. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الثاني للتقاطع. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


يحصل على بنية `com.aspose.imaging.Rectangle` تحتوي على اتحاد بنيتين `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الأول للاتحاد. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الثاني للاتحاد. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


يفحص ما إذا كانت بنيتان `com.aspose.imaging.Rectangle` لهما نفس الموقع والحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` الموجود على يسار عامل المساواة. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` الموجود على يمين عامل المساواة. |

**Returns:**
منطقي - يُعيد هذا العامل true إذا كان الهيكلان `com.aspose.imaging.Rectangle` يمتلكان خصائص `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Width` و `com.aspose.imaging.Rectangle.Height` متساوية.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


يفحص ما إذا كانت بنيتان `com.aspose.imaging.Rectangle` تختلفان في الموقع أو الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` الموجود على يسار عامل عدم المساواة. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` الموجود على يمين عامل عدم المساواة. |

**Returns:**
منطقي - يُعيد هذا العامل true إذا كان أي من خصائص `com.aspose.imaging.Rectangle.X` أو `com.aspose.imaging.Rectangle.Y` أو `com.aspose.imaging.Rectangle.Width` أو `com.aspose.imaging.Rectangle.Height` للهيكلين `com.aspose.imaging.Rectangle` غير متساوية؛ وإلا false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


ينشئ بنية `com.aspose.imaging.Rectangle` بالمواقع المحددة للحواف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | int | الإحداثي السيني للزاوية العلوية اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`. |
| أعلى | int | الإحداثي الصادي للزاوية العلوية اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`. |
| يمين | int | الإحداثي السيني للزاوية السفلية اليمنى لهذا الهيكل `com.aspose.imaging.Rectangle`. |
| أسفل | int | الإحداثي الصادي للزاوية السفلية اليمنى لهذا الهيكل `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


يحصل أو يضبط إحداثيات الزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


يحصل أو يضبط إحداثيات الزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | `Point` الذي يمثل الزاوية العلوية اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`. |

### getSize() {#getSize--}
```
public Size getSize()
```


يحصل أو يضبط حجم هذا الـ `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


يحصل أو يضبط حجم هذا الـ `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | `com.aspose.imaging.Size` الذي يمثل العرض والارتفاع لهذا الهيكل `com.aspose.imaging.Rectangle`. |

### getX() {#getX--}
```
public int getX()
```


يحصل أو يضبط الإحداثي السيني للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - الإحداثي السيني للزاوية العلوية اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


يحصل أو يضبط الإحداثي السيني للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي السيني للزاوية العلوية اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`. |

### getY() {#getY--}
```
public int getY()
```


يحصل أو يضبط الإحداثي الصادي للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - إحداثي y للزاوية العلوية اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


يحصل أو يضبط الإحداثي الصادي للزاوية العليا اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي الصادي للزاوية العلوية اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض هذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - عرض هذا الهيكل `com.aspose.imaging.Rectangle`.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يضبط عرض هذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | عرض هذا الهيكل `com.aspose.imaging.Rectangle`. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يضبط ارتفاع هذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - ارتفاع هذا الهيكل `com.aspose.imaging.Rectangle`.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يضبط ارتفاع هذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | ارتفاع هذا الهيكل `com.aspose.imaging.Rectangle`. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


يحصل أو يضبط الإحداثي السيني للحافة اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - إحداثي x للحافة اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


يحصل أو يضبط الإحداثي السيني للحافة اليسرى لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحداثي x للحافة اليسرى لهذا الهيكل `com.aspose.imaging.Rectangle`. |

### getTop() {#getTop--}
```
public int getTop()
```


يحصل أو يضبط الإحداثي الصادي للحافة العليا لهذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - إحداثي y للحافة العلوية لهذا الهيكل `com.aspose.imaging.Rectangle`.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


يحصل أو يضبط الإحداثي الصادي للحافة العليا لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحداثي y للحافة العلوية لهذا الهيكل `com.aspose.imaging.Rectangle`. |

### getRight() {#getRight--}
```
public int getRight()
```


يحصل أو يضبط الإحداثي السيني الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Width` لهذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - إحداثي x الذي هو مجموع `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Width` لهذا `com.aspose.imaging.Rectangle`.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


يحصل أو يضبط الإحداثي السيني الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Width` لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحداثي x الذي هو مجموع `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Width` لهذا `com.aspose.imaging.Rectangle`. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


يحصل أو يضبط الإحداثي الصادي الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Height` لهذه البنية `com.aspose.imaging.Rectangle`.

**Returns:**
int - إحداثي y الذي هو مجموع `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Height` لهذا `com.aspose.imaging.Rectangle`.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


يحصل أو يضبط الإحداثي الصادي الذي هو مجموع قيمتي الخاصيتين `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Height` لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحداثي y الذي هو مجموع `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Height` لهذا `com.aspose.imaging.Rectangle`. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذه البنية `com.aspose.imaging.Rectangle` تساوي الصفر.

**Returns:**
boolean - تُعيد هذه الخاصية true إذا كانت خصائص `com.aspose.imaging.Rectangle.Width` و `com.aspose.imaging.Rectangle.Height` و `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Y` لهذا `com.aspose.imaging.Rectangle` جميعها تساوي الصفر؛ وإلا false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للنقطة المراد اختبارها. |
| ص | int | إحداثي y للنقطة المراد اختبارها. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المعرفة بـ `x` و `y` موجودة داخل هذا الهيكل `com.aspose.imaging.Rectangle`؛ وإلا false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `com.aspose.imaging.Point` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة الممثلة بـ `point` موجودة داخل هذا الهيكل `com.aspose.imaging.Rectangle`؛ وإلا false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


يحدد ما إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل هذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الـ `com.aspose.imaging.Rectangle` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل هذا الهيكل `com.aspose.imaging.Rectangle`؛ وإلا false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


يوسع هذه البنية `com.aspose.imaging.Rectangle` بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | المقدار لتوسيع هذا `com.aspose.imaging.Rectangle` أفقيًا. |
| الارتفاع | int | المقدار لتوسيع هذا `com.aspose.imaging.Rectangle` رأسيًا. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


يوسع هذه البنية `com.aspose.imaging.Rectangle` بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | المقدار لتوسيع هذا المستطيل. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


يستبدل هذه البنية `com.aspose.imaging.Rectangle` بتقاطعها مع الـ `com.aspose.imaging.Rectangle` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الـ `com.aspose.imaging.Rectangle` للتقاطع معه. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كان هناك أي تقاطع؛ وإلا false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | المقدار لإزاحة الموقع. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإزاحة الأفقية. |
| ص | int | الإزاحة العمودية. |

### normalize() {#normalize--}
```
public void normalize()
```


يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والأعلى أصغر من الأسفل.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان `obj` بنية `com.aspose.imaging.Rectangle` لها نفس الموقع والحجم لهذه البنية `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ `System.Object` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كان `obj` هو هيكل `com.aspose.imaging.Rectangle` وكانت خصائصه `com.aspose.imaging.Rectangle.X` و `com.aspose.imaging.Rectangle.Y` و `com.aspose.imaging.Rectangle.Width` و `com.aspose.imaging.Rectangle.Height` مساوية للخصائص المقابلة لهذا الهيكل `com.aspose.imaging.Rectangle`؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذا الهيكل `com.aspose.imaging.Rectangle`.

**Returns:**
int - عدد صحيح يمثل رمز التجزئة لهذا المستطيل.
### toString() {#toString--}
```
public String toString()
```


يقوم بتحويل خصائص هذا `com.aspose.imaging.Rectangle` إلى سلسلة قابلة للقراءة البشرية.

**Returns:**
java.lang.String - سلسلة تحتوي على الموضع والعرض والارتفاع لهذا الهيكل `com.aspose.imaging.Rectangle`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
