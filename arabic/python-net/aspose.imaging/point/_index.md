---
title: "فئة Point"
type: docs
weight: 6960
url: /ar/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Point()](#Point__1) | ينشئ مثيلاً جديدًا لفئة Point |
| [Point(dw)](#Point_dw_2) | ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام إحداثيات محددة بقيمة عدد صحيح. |
| [Point(size)](#Point_size_3) | ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) من الهيكل [Size](/imaging/python-net/aspose.imaging/size/). |
| [Point(x, y)](#Point_x_y_4) | ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) بالإحداثيات المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | يحصل على مثيل جديد للهيكل [Point](/imaging/python-net/aspose.imaging/point/) الذي تكون قيم [Point.x](/imaging/python-net/aspose.imaging/point/) و [Point.y](/imaging/python-net/aspose.imaging/point/) فيه مضبوطة على الصفر. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Point](/imaging/python-net/aspose.imaging/point/) فارغًا. |
| x | int | r/w | يحصل أو يضبط الإحداثي x لهذا [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | يحصل أو يضبط الإحداثي y لهذا [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | يضيف الـ[Size](/imaging/python-net/aspose.imaging/size/) المحدد إلى الـ[Point](/imaging/python-net/aspose.imaging/point/). |
| [ceiling(point)](#ceiling_point_2) | يحوّل الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) المحدد إلى [Point](/imaging/python-net/aspose.imaging/point/) عن طريق تقريب قيم الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) إلى القيم الصحيحة الأعلى. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام إحداثيات محددة بقيمة عدد صحيح. |
| [create_from_size(size)](#create_from_size_size_4) | ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) من الهيكل [Size](/imaging/python-net/aspose.imaging/size/). |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | يفكّ بنية كائن Point المعبأ في كائن طويل إلى قيم X و Y صحيحة منفصلة. |
| [offset(dx, dy)](#offset_dx_dy_6) | ينقل هذا [Point](/imaging/python-net/aspose.imaging/point/) بالمقدار المحدد. |
| [offset(point)](#offset_point_7) | ينقل هذا [Point](/imaging/python-net/aspose.imaging/point/) بواسطة الـ[Point](/imaging/python-net/aspose.imaging/point/) المحدد. |
| [round(point)](#round_point_8) | يحوّل الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) المحدد إلى كائن [Point](/imaging/python-net/aspose.imaging/point/) عن طريق تقريب قيم الـ[Point](/imaging/python-net/aspose.imaging/point/) إلى أقرب عدد صحيح. |
| [subtract(point, size)](#subtract_point_size_9) | يعيد نتيجة طرح الـ[Size](/imaging/python-net/aspose.imaging/size/) المحدد من الـ[Point](/imaging/python-net/aspose.imaging/point/). |
| [to_long()](#to_long__10) | حوّل هذا Point إلى قيمة طويلة واحدة، تحتوي على إحداثيات X و Y في البتات العليا والسفلى. |
| [truncate(point)](#truncate_point_11) | يحوّل الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) المحدد إلى [Point](/imaging/python-net/aspose.imaging/point/) عن طريق قطع قيم الـ[Point](/imaging/python-net/aspose.imaging/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

ينشئ مثيلاً جديدًا لفئة Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام إحداثيات محددة بقيمة عدد صحيح.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dw | int | عدد صحيح 32‑بت يحدد الإحداثيات للنقطة الجديدة. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) من الهيكل [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | يحتوي على إحداثيات النقطة الجديدة. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) بالإحداثيات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الموضع الأفقي للنقطة. |
| y | int | الموضع الرأسي للنقطة. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

يضيف الـ[Size](/imaging/python-net/aspose.imaging/size/) المحدد إلى الـ[Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | الـ[Point](/imaging/python-net/aspose.imaging/point/) للإضافة إليه. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | الـ[Size](/imaging/python-net/aspose.imaging/size/) للإضافة إلى الـ_النقطة_. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | الـ[Point](/imaging/python-net/aspose.imaging/point/) الذي هو نتيجة عملية الجمع. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

يحوّل الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) المحدد إلى [Point](/imaging/python-net/aspose.imaging/point/) عن طريق تقريب قيم الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) إلى القيم الصحيحة الأعلى.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) للتحويل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | الـ [Point](/imaging/python-net/aspose.imaging/point/) الذي تتحول إليه هذه الطريقة. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام إحداثيات محددة بقيمة عدد صحيح.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dw | int | عدد صحيح 32‑بت يحدد الإحداثيات للنقطة الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

ينشئ مثيلاً جديدًا للهيكل [Point](/imaging/python-net/aspose.imaging/point/) من الهيكل [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | يحتوي على إحداثيات النقطة الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

يفكّ بنية كائن Point المعبأ في كائن طويل إلى قيم X و Y صحيحة منفصلة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| packed_point | int | كائن Point المعبأ في قيمة طويلة واحدة. |
| x | int[] | القيمة المستخرجة من قيمة X المعبأة لنقطة Point. |
| y | int[] | القيمة المستخرجة من قيمة Y المعبأة لنقطة Point. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

ينقل هذا [Point](/imaging/python-net/aspose.imaging/point/) بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | int | المقدار لإزاحة إحداثي x. |
| dy | int | المقدار لإزاحة إحداثي y. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

ينقل هذا [Point](/imaging/python-net/aspose.imaging/point/) بواسطة الـ[Point](/imaging/python-net/aspose.imaging/point/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | الـ [Point](/imaging/python-net/aspose.imaging/point/) المستخدم لإزاحة هذا الـ [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

يحوّل الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) المحدد إلى كائن [Point](/imaging/python-net/aspose.imaging/point/) عن طريق تقريب قيم الـ[Point](/imaging/python-net/aspose.imaging/point/) إلى أقرب عدد صحيح.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) للتحويل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | الـ [Point](/imaging/python-net/aspose.imaging/point/) الذي تتحول إليه هذه الطريقة. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

يعيد نتيجة طرح الـ[Size](/imaging/python-net/aspose.imaging/size/) المحدد من الـ[Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | الـ [Point](/imaging/python-net/aspose.imaging/point/) الذي سيُطرح منه. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | الـ [Size](/imaging/python-net/aspose.imaging/size/) للطرح من الـ _point_. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | الـ [Point](/imaging/python-net/aspose.imaging/point/) الذي هو نتيجة عملية الطرح. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

حوّل هذا Point إلى قيمة طويلة واحدة، تحتوي على إحداثيات X و Y في البتات العليا والسفلى.

**Returns**

| نوع | الوصف |
| :- | :- |
| int | كائن Point المعبأ في قيمة طويلة واحدة. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

يحوّل الـ[PointF](/imaging/python-net/aspose.imaging/pointf/) المحدد إلى [Point](/imaging/python-net/aspose.imaging/point/) عن طريق قطع قيم الـ[Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) للتحويل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | الـ [Point](/imaging/python-net/aspose.imaging/point/) الذي تتحول إليه هذه الطريقة. |


