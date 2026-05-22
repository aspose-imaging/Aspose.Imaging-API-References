---
title: "فئة RectangleF"
type: docs
weight: 7130
url: /ar/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | يُنشئ مثيلًا جديدًا لفئة RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | يُنشئ مثيلًا جديدًا للهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) مع الموقع والحجم المحددين. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | يُنشئ مثيلًا جديدًا للهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) مع الموقع والحجم المحددين. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bottom | float | r/w | يحصل أو يعيّن إحداثي y الذي هو مجموع [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) و [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على مثيل جديد للهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحتوي على قيم [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/)، [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/)، [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) و [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) مضبوطة على الصفر. |
| height | float | r/w | يحصل أو يعيّن ارتفاع هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كانت خاصية [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) أو [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) لها قيمة صفر. |
| left | float | r/w | يحصل أو يعيّن إحداثي x للحافة اليسرى لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن إحداثيات الزاوية العلوية اليسرى لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| right | float | r/w | يحصل أو يعيّن إحداثي x الذي هو مجموع [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) و [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | يحصل أو يعيّن حجم هذا [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | يحصل أو يعيّن إحداثي y للحافة العلوية لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| width | float | r/w | يحصل أو يعيّن عرض هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| x | float | r/w | يحصل أو يعيّن إحداثي x للزاوية العلوية اليسرى لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| y | float | r/w | يحصل أو يعيّن إحداثي y للزاوية العلوية اليسرى لهذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [contains(point)](#contains_point_1) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(rect)](#contains_rect_2) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_point_f(point)](#contains_point_f_point_4) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | ينشئ هيكلاً من نوع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) مع الزاوية العلوية اليسرى والزاوية السفلية اليمنى في المواقع المحددة. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | ينشئ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) جديدًا من نقطتين محددتين. سيكون رُؤوس [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المُنشأ مساوية للنقطتين _point1_ و _point2_. عادةً ما تكون هذه هي الرؤوس المتقابلة. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | ينشئ ويعيد نسخة مُضخَّمة من الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد. تُضاعف النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل. |
| [inflate(size)](#inflate_size_9) | يضخم هذا [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) بالمقدار المحدد. |
| [inflate(x, y)](#inflate_x_y_10) | يضخم هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) بالمقدار المحدد. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | ينشئ ويعيد نسخة مُضخَّمة من الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد. تُضاعف النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل. |
| [intersect(a, b)](#intersect_a_b_12) | يعيد هيكلاً من نوع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) فارغ. |
| [intersect(rect)](#intersect_rect_13) | يستبدل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) بتقاطع نفسه مع الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | يعيد هيكلاً من نوع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) فارغ. |
| [intersects_with(rect)](#intersects_with_rect_15) | يحدد ما إذا كان هذا المستطيل يتقاطع مع _rect_. |
| normalize() | يقوم بتطبيع المستطيل عن طريق جعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أعلى من الأسفل. |
| [offset(pos)](#offset_pos_16) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(x, y)](#offset_x_y_17) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [union(a, b)](#union_a_b_18) | ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

يُنشئ مثيلًا جديدًا لفئة RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

يُنشئ مثيلًا جديدًا للهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) مع الموقع والحجم المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تمثل الزاوية العلوية اليسرى للمنطقة المستطيلة. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | حجم [SizeF](/imaging/python-net/aspose.imaging/sizef/) يمثل عرض وارتفاع المنطقة المستطيلة. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

يُنشئ مثيلًا جديدًا للهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) مع الموقع والحجم المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | إحداثي x للزاوية العلوية اليسرى للمستطيل. |
| y | float | إحداثي y للزاوية العلوية اليسرى للمستطيل. |
| width | float | عرض المستطيل. |
| height | float | ارتفاع المستطيل. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة الممثلة بالمعامل _point_ موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); وإلا false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ _rect_ مُضمنة بالكامل داخل المنطقة المستطيلة الممثلة بـ هذا [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); وإلا false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المعرفة بـ _x_ و _y_ مُضمنة داخل بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) هذه؛ وإلا false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة الممثلة بالمعامل _point_ موجودة داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); وإلا false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها _rect_ موجودة بالكامل داخل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ _rect_ مُضمنة بالكامل داخل المنطقة المستطيلة الممثلة بـ هذا [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); وإلا false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

ينشئ هيكلاً من نوع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) مع الزاوية العلوية اليسرى والزاوية السفلية اليمنى في المواقع المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| اليسار | float | الإحداثي السيني للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| الأعلى | float | الإحداثي الصادي للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| اليمين | float | الإحداثي السيني للزاوية السفلية اليمنى للمنطقة المستطيلة. |
| الأسفل | float | الإحداثي الصادي للزاوية السفلية اليمنى للمنطقة المستطيلة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | الـ [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الجديد الذي تُنشئه هذه الطريقة. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

ينشئ [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) جديدًا من نقطتين محددتين. سيكون رُؤوس [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المُنشأ مساوية للنقطتين _point1_ و _point2_. عادةً ما تكون هذه هي الرؤوس المتقابلة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | النقطة الأولى [Point](/imaging/python-net/aspose.imaging/point/) للمستطيل الجديد. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | النقطة الثانية [Point](/imaging/python-net/aspose.imaging/point/) للمستطيل الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | مستطيل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) تم إنشاؤه حديثًا. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

ينشئ ويعيد نسخة مُضخَّمة من الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد. تُضاعف النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي سيُنسخ. هذا المستطيل غير معدل. |
| x | float | القيمة لتوسيع نسخة المستطيل أفقياً. |
| y | float | القيمة لتوسيع نسخة المستطيل عمودياً. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المُوسع. |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

يضخم هذا [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | القيمة لتوسيع هذا المستطيل. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

يضخم هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | القيمة لتوسيع بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) هذه أفقياً. |
| y | float | القيمة لتوسيع بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) هذه عمودياً. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

ينشئ ويعيد نسخة مُضخَّمة من الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد. تُضاعف النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي سيُنسخ. هذا المستطيل غير معدل. |
| x | float | القيمة لتوسيع نسخة المستطيل أفقياً. |
| y | float | القيمة لتوسيع نسخة المستطيل عمودياً. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المُوسع. |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

يعيد هيكلاً من نوع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) فارغ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الأول للتقاطع. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الثاني للتقاطع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | الهيكل الثالث [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يمثل حجمه المنطقة المتداخلة بين المستطيلين المحددين. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

يستبدل هذا الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) بتقاطع نفسه مع الهيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل للتقاطع. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

يعيد هيكلاً من نوع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) فارغ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الأول للتقاطع. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الثاني للتقاطع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | الهيكل الثالث [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يمثل حجمه المنطقة المتداخلة بين المستطيلين المحددين. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

يحدد ما إذا كان هذا المستطيل يتقاطع مع _rect_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كان هناك أي تقاطع. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | القيمة لإزاحة الموقع. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | القيمة لإزاحة الموقع أفقياً. |
| y | float | القيمة لإزاحة الموقع عمودياً. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الأول للاتحاد. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الثاني للاتحاد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | الهيكل الثالث [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحتوي على كلا المستطيلين اللذين يشكلان الاتحاد. |


