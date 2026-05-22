---
title: "فئة Size"
type: docs
weight: 7280
url: /ar/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Size()](#Size__1) | ينشئ مثيلاً جديداً لفئة Size |
| [Size(point)](#Size_point_2) | ينشئ مثيلاً جديداً للهيكل [Size](/imaging/python-net/aspose.imaging/size/) من الـ[Point](/imaging/python-net/aspose.imaging/point/) المحدد. |
| [Size(width, height)](#Size_width_height_3) | ينشئ مثيلاً جديداً للهيكل [Size](/imaging/python-net/aspose.imaging/size/) من الأبعاد المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | يحصل على مثيل جديد للهيكل [Size](/imaging/python-net/aspose.imaging/size/) الذي تكون قيم [Size.width](/imaging/python-net/aspose.imaging/size/) و [Size.height](/imaging/python-net/aspose.imaging/size/) فيهما صفر. |
| height | int | r/w | يحصل أو يعيّن المكوّن العمودي لهذا [Size](/imaging/python-net/aspose.imaging/size/). |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Size](/imaging/python-net/aspose.imaging/size/) له عرض وارتفاع يساويان 0. |
| width | int | r/w | يحصل أو يعيّن المكوّن الأفقي لهذا [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | يضيف عرض وارتفاع هيكل [Size] واحد إلى عرض وارتفاع هيكل [Size] آخر. |
| [ceiling(size)](#ceiling_size_2) | يحوّل الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) المحدد إلى هيكل [Size](/imaging/python-net/aspose.imaging/size/) عن طريق تقريب قيم الهيكل [Size](/imaging/python-net/aspose.imaging/size/) إلى أقرب عدد صحيح أعلى. |
| [round(size)](#round_size_3) | يحوّل الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) المحدد إلى هيكل [Size](/imaging/python-net/aspose.imaging/size/) عن طريق تقريب قيم الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) إلى أقرب عدد صحيح. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | يطرح عرض وارتفاع هيكل [Size] واحد من عرض وارتفاع هيكل [Size] آخر. |
| [truncate(size)](#truncate_size_5) | يحوّل الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) المحدد إلى هيكل [Size](/imaging/python-net/aspose.imaging/size/) عن طريق قطع قيم الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) إلى أقرب عدد صحيح أدنى. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

ينشئ مثيلاً جديداً لفئة Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

ينشئ مثيلاً جديداً للهيكل [Size](/imaging/python-net/aspose.imaging/size/) من الـ[Point](/imaging/python-net/aspose.imaging/point/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | الـ[Point](/imaging/python-net/aspose.imaging/point/) الذي يُستخدم لتهيئة هذا [Size](/imaging/python-net/aspose.imaging/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

ينشئ مثيلاً جديداً للهيكل [Size](/imaging/python-net/aspose.imaging/size/) من الأبعاد المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | المكوّن العرضي للـ[Size](/imaging/python-net/aspose.imaging/size/) الجديد. |
| height | int | المكوّن الارتفاعي للـ[Size](/imaging/python-net/aspose.imaging/size/) الجديد. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

يضيف عرض وارتفاع هيكل [Size] واحد إلى عرض وارتفاع هيكل [Size] آخر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | الـ[Size] الأول للإضافة. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | الـ[Size] الثاني للإضافة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | هيكل [Size] هو نتيجة عملية الجمع. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

يحوّل الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) المحدد إلى هيكل [Size](/imaging/python-net/aspose.imaging/size/) عن طريق تقريب قيم الهيكل [Size](/imaging/python-net/aspose.imaging/size/) إلى أقرب عدد صحيح أعلى.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | هيكل [SizeF] لتحويله. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | هيكل [Size] الذي تتحوله هذه الطريقة إليه. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

يحوّل الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) المحدد إلى هيكل [Size](/imaging/python-net/aspose.imaging/size/) عن طريق تقريب قيم الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) إلى أقرب عدد صحيح.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | هيكل [SizeF] لتحويله. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | هيكل [Size] الذي تتحوله هذه الطريقة إليه. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

يطرح عرض وارتفاع هيكل [Size] واحد من عرض وارتفاع هيكل [Size] آخر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | الـ [Size](/imaging/python-net/aspose.imaging/size/) البنية على الجانب الأيسر من عامل الطرح. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | الـ [Size](/imaging/python-net/aspose.imaging/size/) البنية على الجانب الأيمن من عامل الطرح. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | الـ [Size](/imaging/python-net/aspose.imaging/size/) التي هي نتيجة عملية الطرح. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

يحوّل الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) المحدد إلى هيكل [Size](/imaging/python-net/aspose.imaging/size/) عن طريق قطع قيم الهيكل [SizeF](/imaging/python-net/aspose.imaging/sizef/) إلى أقرب عدد صحيح أدنى.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | هيكل [SizeF] لتحويله. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | هيكل [Size] الذي تتحوله هذه الطريقة إليه. |


