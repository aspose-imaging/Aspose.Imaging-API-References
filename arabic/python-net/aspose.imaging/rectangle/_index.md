---
title: "الفئة Rectangle"
type: docs
weight: 7120
url: /ar/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | يُنشئ مثيلاً جديدًا للفئة Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | يُنشئ مثيلاً جديدًا للهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) مع الموقع والحجم المحددين. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | يُنشئ مثيلاً جديدًا للهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) مع الموقع والحجم المحددين. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bottom | int | r/w | يحصل أو يضبط الإحداثي y الذي هو مجموع قيم الخاصيتين [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) و[Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على مثيل جديد للهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي تكون قيم [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/)، [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/)، [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) و[Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) فيه صفر. |
| height | int | r/w | يحصل أو يضبط الارتفاع لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) لها قيم صفر. |
| left | int | r/w | يحصل أو يضبط إحداثي x للحافة اليسرى لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يضبط إحداثيات الزاوية العلوية اليسرى لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | r/w | يحصل أو يضبط إحداثي x الذي هو مجموع قيمتي الخاصيتين [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) و [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | يحصل أو يضبط حجم هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | يحصل أو يضبط إحداثي y للحافة العلوية لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| width | int | r/w | يحصل أو يضبط عرض هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| x | int | r/w | يحصل أو يضبط إحداثي x للزاوية العلوية اليسرى لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | r/w | يحصل أو يضبط إحداثي y للزاوية العلوية اليسرى لهذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | يحوّل الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد إلى هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) عن طريق تقريب قيم [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) إلى أعلى قيمة صحيحة. |
| [contains(point)](#contains_point_2) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(rect)](#contains_rect_3) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_point(point)](#contains_point_point_5) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_rect(rect)](#contains_rect_rect_6) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | ينشئ هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالمواقع المحددة للحواف. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | ينشئ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) جديدًا من نقطتين محددتين. سيكون العمودان الرأسيان للـ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الناتج مساويين للنقطتين _point1_ و _point2_. عادةً ما تكون هاتان القمتان المتقابلتين. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | ينشئ ويعيد نسخة مُضخمة من الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المحدد. تُضخم النسخة بالمقدار المحدد. يظل الهيكل الأصلي [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) دون تعديل. |
| [inflate(size)](#inflate_size_10) | يضخم هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالمقدار المحدد. |
| [inflate(width, height)](#inflate_width_height_11) | يضخم هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالمقدار المحدد. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | ينشئ ويعيد نسخة مُضخمة من الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المحدد. تُضخم النسخة بالمقدار المحدد. يظل الهيكل الأصلي [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) دون تعديل. |
| [intersect(a, b)](#intersect_a_b_13) | يعيد هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) ثالث يمثل تقاطع هيكلين آخرين من نوع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). إذا لم يكن هناك تقاطع، يتم إرجاع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) فارغ. |
| [intersect(rect)](#intersect_rect_14) | يستبدل هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالتقاطع بينه وبين الـ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المحدد. |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | يعيد هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) ثالث يمثل تقاطع هيكلين آخرين من نوع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). إذا لم يكن هناك تقاطع، يتم إرجاع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) فارغ. |
| [intersects_with(rect)](#intersects_with_rect_16) | يحدد ما إذا كان هذا المستطيل يتقاطع مع _rect_. |
| normalize() | يقوم بتطبيع المستطيل عن طريق جعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أعلى من الأسفل. |
| [offset(pos)](#offset_pos_17) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(x, y)](#offset_x_y_18) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [round(value)](#round_value_19) | يحوّل الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد إلى [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) عن طريق تقريب قيم الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) إلى أقرب قيمة صحيحة. |
| [truncate(value)](#truncate_value_20) | يحوّل الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد إلى [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) عن طريق حذف الجزء العشري من قيم الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union(a, b)](#union_a_b_21) | يحصل على هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) يحتوي على اتحاد هيكلين من نوع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

يُنشئ مثيلاً جديدًا للفئة Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

يُنشئ مثيلاً جديدًا للهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) مع الموقع والحجم المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) يمثل الزاوية العلوية اليسرى للمنطقة المستطيلة. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) يمثل العرض والارتفاع للمنطقة المستطيلة. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

يُنشئ مثيلاً جديدًا للهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) مع الموقع والحجم المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | إحداثي x للزاوية العلوية اليسرى للمستطيل. |
| y | int | إحداثي y للزاوية العلوية اليسرى للمستطيل. |
| width | int | عرض المستطيل. |
| height | int | ارتفاع المستطيل. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

يحوّل الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد إلى هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) عن طريق تقريب قيم [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) إلى أعلى قيمة صحيحة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي سيُحوَّل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | يعيد [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة الممثلة بـ _point_ موجودة داخل بنية هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); وإلا false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | الـ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ _rect_ موجودة بالكامل داخل بنية هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); وإلا false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المعرفة بـ _x_ و _y_ موجودة داخل بنية هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); وإلا false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة الممثلة بـ _point_ موجودة داخل بنية هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); وإلا false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | الـ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ _rect_ موجودة بالكامل داخل بنية هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); وإلا false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

ينشئ هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالمواقع المحددة للحواف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| left | int | الإحداثي x للزاوية العلوية اليسرى لهذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الهيكل. |
| top | int | الإحداثي y للزاوية العلوية اليسرى لهذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الهيكل. |
| right | int | الإحداثي x للزاوية السفلية اليمنى لهذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الهيكل. |
| bottom | int | الإحداثي y للزاوية السفلية اليمنى لهذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الهيكل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الجديد الذي تُنشئه هذه الطريقة. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

ينشئ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) جديدًا من نقطتين محددتين. سيكون العمودان الرأسيان للـ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الناتج مساويين للنقطتين _point1_ و _point2_. عادةً ما تكون هاتان القمتان المتقابلتين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | النقطة الأولى [Point](/imaging/python-net/aspose.imaging/point/) للمستطيل الجديد. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | النقطة الثانية [Point](/imaging/python-net/aspose.imaging/point/) للمستطيل الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) تم إنشاؤه حديثًا. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

ينشئ ويعيد نسخة مُضخمة من الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المحدد. تُضخم النسخة بالمقدار المحدد. يظل الهيكل الأصلي [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) دون تعديل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) للبدء به. هذا المستطيل غير معدل. |
| x | int | القيمة لتوسيع هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) أفقياً. |
| y | int | القيمة لتوسيع هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) رأسياً. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المُوسّع. |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

يضخم هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | القيمة لتوسيع هذا المستطيل. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

يضخم هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | القيمة لتوسيع هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) أفقياً. |
| height | int | القيمة لتوسيع هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) رأسياً. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

ينشئ ويعيد نسخة مُضخمة من الهيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المحدد. تُضخم النسخة بالمقدار المحدد. يظل الهيكل الأصلي [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) دون تعديل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) للبدء به. هذا المستطيل غير معدل. |
| x | int | القيمة لتوسيع هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) أفقياً. |
| y | int | القيمة لتوسيع هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) رأسياً. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المُوسّع. |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

يعيد هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) ثالث يمثل تقاطع هيكلين آخرين من نوع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). إذا لم يكن هناك تقاطع، يتم إرجاع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) فارغ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الأول للتقاطع. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الثاني للتقاطع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) يمثل تقاطع _a_ و _b_. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

يستبدل هذا [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) بالتقاطع بينه وبين الـ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) للتقاطع معه. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

يعيد هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) ثالث يمثل تقاطع هيكلين آخرين من نوع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). إذا لم يكن هناك تقاطع، يتم إرجاع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) فارغ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الأول للتقاطع. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الثاني للتقاطع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) يمثل تقاطع _a_ و _b_. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

يحدد ما إذا كان هذا المستطيل يتقاطع مع _rect_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كان هناك أي تقاطع، وإلا false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | القيمة لإزاحة الموقع. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإزاحة الأفقية. |
| y | int | الإزاحة الرأسية. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

يحوّل الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد إلى [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) عن طريق تقريب قيم الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) إلى أقرب قيمة صحيحة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) للتحويل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) جديد. |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

يحوّل الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد إلى [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) عن طريق حذف الجزء العشري من قيم الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) للتحويل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) جديد. |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

يحصل على هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) يحتوي على اتحاد هيكلين من نوع [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الأول للاتحاد. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الثاني للاتحاد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | بنية [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) التي تحصر اتحاد البنيتين [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


