---
title: "فئة Pen"
type: docs
weight: 6890
url: /ar/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) المحدد. |
| [Pen(brush, width)](#Pen_brush_width_2) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحدد. |
| [Pen(color)](#Pen_color_3) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام اللون المحدد. |
| [Pen(color, width)](#Pen_color_width_4) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام الخصائص [Pen.color](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | يحصل أو يضبط المحاذاة لهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | يحصل أو يضبط [Pen.brush](/imaging/python-net/aspose.imaging/pen/) الذي يحدد سمات هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط لون هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| compound_array | float[] | r/w | يحصل أو يضبط مصفوفة من القيم التي تحدد قلمًا مركبًا. يرسم القلم المركب خطًا مركبًا مكوّنًا من خطوط موازية وفراغات. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | يسترجع أو يعيّن المسافة من بداية الخط إلى بداية نمط الشرط. |
| dash_pattern | float[] | r/w | يسترجع أو يعيّن مصفوفة من الشرطات والمسافات المخصصة. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | يسترجع أو يعيّن النمط المستخدم للخطوط المتقطعة المرسومة بهذه [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | يسترجع أو يعيّن نمط الطرف المستخدم في نهاية الخطوط المرسومة بهذه [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | يسترجع أو يعيّن نمط الوصل لنهايات خطين متتاليين مرسومين بهذه [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | يسترجع أو يعيّن الحد الأقصى لسماكة الوصل عند الزاوية المشطوفة. |
| opacity | float | r/w | يحصل أو يضبط شفافية الكائن. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الكائن مرئي بالكامل، والقيمة 1 تعني أن الكائن غير شفاف تمامًا. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | يسترجع نمط الخطوط المرسومة بهذه [Pen](/imaging/python-net/aspose.imaging/pen/). |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | يسترجع أو يعيّن نمط الطرف المستخدم في بداية الخطوط المرسومة بهذه [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يسترجع أو يعيّن نسخة من التحويل الهندسي لهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | r/w | يسترجع أو يعيّن عرض هذا [Pen](/imaging/python-net/aspose.imaging/pen/)، بوحدات كائن Graphics المستخدم للرسم. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) المحدد. |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحدد. |
| [create_with_color(color)](#create_with_color_color_3) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام اللون المحدد. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام الخصائص [Pen.color](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحددة. |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | يضرب مصفوفة التحويل لهذا [Pen](/imaging/python-net/aspose.imaging/pen/) بالمصفوفة المحددة [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | يضرب مصفوفة التحويل لهذا [Pen](/imaging/python-net/aspose.imaging/pen/) بالمصفوفة المحددة [Matrix](/imaging/python-net/aspose.imaging/matrix/) بالترتيب المحدد. |
| reset_transform() | يعيد تعيين مصفوفة التحويل الهندسي لهذا [Pen](/imaging/python-net/aspose.imaging/pen/) إلى الهوية. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | يدور التحويل الهندسي المحلي بالزاوية المحددة. تُضيف هذه الطريقة الدوران إلى بداية التحويل. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | يقوم بتوسيع التحويل الهندسي المحلي بالعوامل المحددة. تُضيف هذه الطريقة مصفوفة القياس إلى بداية التحويل. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | يقوم بتوسيع التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | يضبط القيم التي تحدد نمط الطرف المستخدم لإنهاء الخطوط المرسومة بهذه [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تُضيف هذه الطريقة الإزاحة إلى بداية التحويل. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | ‏[Pen.brush](/imaging/python-net/aspose.imaging/pen/) يحدد خصائص التعبئة لهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | ‏[Pen.brush](/imaging/python-net/aspose.imaging/pen/) يحدد خصائص هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | عرض الـ [Pen](/imaging/python-net/aspose.imaging/pen/) الجديد. |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام اللون المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | ‏[Pen.color](/imaging/python-net/aspose.imaging/pen/) يحدد لون هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام الخصائص [Pen.color](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | ‏[Pen.color](/imaging/python-net/aspose.imaging/pen/) يحدد لون هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | قيمة تشير إلى عرض هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | ‏[Pen.brush](/imaging/python-net/aspose.imaging/pen/) يحدد خصائص التعبئة لهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام [Pen.brush](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | ‏[Pen.brush](/imaging/python-net/aspose.imaging/pen/) يحدد خصائص هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | عرض الـ [Pen](/imaging/python-net/aspose.imaging/pen/) الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام اللون المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | ‏[Pen.color](/imaging/python-net/aspose.imaging/pen/) يحدد لون هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

ينشئ نسخة جديدة من الفئة [Pen](/imaging/python-net/aspose.imaging/pen/) باستخدام الخصائص [Pen.color](/imaging/python-net/aspose.imaging/pen/) و[Pen.width](/imaging/python-net/aspose.imaging/pen/) المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | ‏[Pen.color](/imaging/python-net/aspose.imaging/pen/) يحدد لون هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | قيمة تشير إلى عرض هذا [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

يضرب مصفوفة التحويل لهذا [Pen](/imaging/python-net/aspose.imaging/pen/) بالمصفوفة المحددة [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | كائن [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُستخدم لضرب مصفوفة التحويل. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

يضرب مصفوفة التحويل لهذا [Pen](/imaging/python-net/aspose.imaging/pen/) بالمصفوفة المحددة [Matrix](/imaging/python-net/aspose.imaging/matrix/) بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُستخدم لضرب مصفوفة التحويل. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب الذي يتم فيه تنفيذ عملية الضرب. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

يدور التحويل الهندسي المحلي بالزاوية المحددة. تُضيف هذه الطريقة الدوران إلى بداية التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد ما إذا كان يجب إضافة أو إلحاق مسبق لمصفوفة الدوران. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

يقوم بتوسيع التحويل الهندسي المحلي بالعوامل المحددة. تُضيف هذه الطريقة مصفوفة القياس إلى بداية التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | العامل الذي يتم من خلاله تحجيم التحويل في اتجاه المحور x. |
| sy | float | العامل الذي يتم من خلاله تحجيم التحويل في اتجاه المحور y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

يقوم بتوسيع التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | العامل الذي يتم من خلاله تحجيم التحويل في اتجاه المحور x. |
| sy | float | العامل الذي يتم من خلاله تحجيم التحويل في اتجاه المحور y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | قائمة [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) التي تحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التحجيم. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

يضبط القيم التي تحدد نمط الطرف المستخدم لإنهاء الخطوط المرسومة بهذه [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | [LineCap](/imaging/python-net/aspose.imaging/linecap/) يمثل نمط الغطاء الذي يُستخدم في بداية الخطوط المرسومة بهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | [LineCap](/imaging/python-net/aspose.imaging/linecap/) يمثل نمط الغطاء الذي يُستخدم في نهاية الخطوط المرسومة بهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | [LineCap](/imaging/python-net/aspose.imaging/linecap/) يمثل نمط الغطاء الذي يُستخدم في بداية أو نهاية الخطوط المتقطعة المرسومة بهذا [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تُضيف هذه الطريقة الإزاحة إلى بداية التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب (إلحاق مسبق أو إلحاق) الذي يتم تطبيق الإزاحة به. |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# إنشاء نسخة من BmpOptions وتعيين خصائصه المتنوعة
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# إنشاء نسخة من FileCreateSource وتعيينها كمصدر للنسخة من BmpOptions
# المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه IsTemporal أم لا
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# إنشاء نسخة من Image في المسار المحدد
with Image.create(bmpOptions, 500, 500) as image:
	# إنشاء نسخة من Graphics وتهيئتها باستخدام كائن Image
	graphics = Graphics(image)
	# مسح سطح Graphics بلون أبيض
	graphics.clear(Color.white)
	#إنشاء نسخة من Pen باللون الأحمر وعرض 5
	pen = Pen(Color.red, 5.0);
	# إنشاء نسخة من HatchBrush وتعيين خصائصه
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# إنشاء نسخة من Pen
	# قم بتهيئتها باستخدام كائن HatchBrush والعرض
	brusedpen = Pen(brush, 5.0)
	# ارسم مستطيلات عن طريق تحديد كائن Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# ارسم مستطيلات عن طريق تحديد كائن Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# احفظ جميع التغييرات.
	image.save()


```

