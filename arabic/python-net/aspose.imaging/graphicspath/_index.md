---
title: "فئة GraphicsPath"
type: docs
weight: 5040
url: /ar/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل أو يضبط حدود الكائن. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | يحصل على أشكال المسار. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | يحصل أو يضبط تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد كيفية تعبئة داخل الأشكال في هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | يضيف شكلاً جديدًا. |
| [add_figures(figures)](#add_figures_figures_2) | يضيف أشكالًا جديدة. |
| [add_path(adding_path)](#add_path_adding_path_3) | يضيف [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) المحدد إلى هذا المسار. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | يضيف [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) المحدد إلى هذا المسار. |
| [deep_clone()](#deep_clone__5) | ينفذ استنساخًا عميقًا لهذا مسار الرسومات. |
| flatten() | يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة. |
| [flatten(matrix)](#flatten_matrix_6) | يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) إلى سلسلة من القطع الخطية المتصلة. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | يحوّل كل منحنى في هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) إلى سلسلة من القطع الخطية المتصلة. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | يحصل على حدود الكائن. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point)](#is_visible_point_26) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(point)](#is_visible_point_27) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_30) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_31) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) في منطقة القص المرئية للرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) في منطقة القص المرئية للرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point(point)](#is_visible_point_point_34) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)، باستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) في منطقة القص المرئية للرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_42) | يزيل شكلاً. |
| [remove_figures(figures)](#remove_figures_figures_43) | يزيل الأشكال. |
| reset() | يفرغ مسار الرسومات ويضبط [FillMode](/imaging/python-net/aspose.imaging/fillmode/) إلى [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | يعكس ترتيب الأشكال، والأشكال، والنقاط في كل شكل من هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [transform(transform)](#transform_transform_44) | يطبق التحويل المحدد على الشكل. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen)](#widen_pen_49) | يضيف مخططًا إضافيًا إلى المسار. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | يضيف مخططًا إضافيًا إلى [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | يستبدل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | الأشكال للتهيئة منها. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | الأشكال للتهيئة منها. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | وضع التعبئة. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | وضع التعبئة. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

يضيف شكلاً جديدًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | الشكل للإضافة. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

يضيف أشكالًا جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | الأشكال للإضافة. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

يضيف [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) المحدد إلى هذا المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | الـ [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) للإضافة. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

يضيف [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) المحدد إلى هذا المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | الـ [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) للإضافة. |
| اتصال | bool | قيمة منطقية تحدد ما إذا كان الشكل الأول في المسار المضاف جزءًا من الشكل الأخير في هذا المسار. قيمة true تشير إلى أن الشكل الأول في المسار المضاف جزء من الشكل الأخير في هذا المسار. قيمة false تشير إلى أن الشكل الأول في المسار المضاف منفصل عن الشكل الأخير في هذا المسار. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

ينفذ استنساخًا عميقًا لهذا مسار الرسومات.

**Returns**

| نوع | الوصف |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | نسخة عميقة من مسار الرسومات. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) إلى سلسلة من القطع الخطية المتصلة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | مصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) لتحويل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) قبل التسوية. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

يحوّل كل منحنى في هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) إلى سلسلة من القطع الخطية المتصلة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | مصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) لتحويل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) قبل التسوية. |
| السطحية | float | يحدد الحد الأقصى للخطأ المسموح بين المنحنى وتقريبه المسطح. القيمة الافتراضية هي 0.25. تقليل قيمة السطحية سيزيد عدد مقاطع الخط في التقريب. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | حدود الكائن المقدرة. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | حدود الكائن المقدرة. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة [PointF](/imaging/python-net/aspose.imaging/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة [Point](/imaging/python-net/aspose.imaging/point/) تحدد الموقع للاختبار. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/) واستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم [Pen](/imaging/python-net/aspose.imaging/pen/) للاختبار. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) عند رسمه بالقلم المحدد [Pen](/imaging/python-net/aspose.imaging/pen/); وإلا، false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | عنصر [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل النقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | عنصر [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل النقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | عنصر [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل النقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا؛ وإلا، false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | عنصر [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل النقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا؛ وإلا، false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) في منطقة القص المرئية للرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) في منطقة القص المرئية للرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | عنصر [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل النقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | عنصر [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل النقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | عنصر [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل النقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا؛ وإلا، false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | عنصر [Point](/imaging/python-net/aspose.imaging/point/) يمثل النقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)، باستخدام الرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | int | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) في منطقة القص المرئية للرسومات المحددة [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | float | الإحداثي الصادي للنقطة التي سيتم اختبارها. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | الـ [Graphics](/imaging/python-net/aspose.imaging/graphics/) لاختبار الرؤية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); وإلا، false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

يزيل شكلاً.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | الشكل المراد إزالته. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

يزيل الأشكال.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | الأشكال المراد إزالتها. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | التحويل المراد تطبيقه. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة _srcRect_ إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | عنصر [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى متوازي أضلاع مُعرّف بواسطة _destPoints_. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة _srcRect_ إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | عنصر [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى متوازي أضلاع مُعرّف بواسطة _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | عنصر [Matrix](/imaging/python-net/aspose.imaging/matrix/) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة _srcRect_ إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | عنصر [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى متوازي أضلاع مُعرّف بواسطة _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | عنصر [Matrix](/imaging/python-net/aspose.imaging/matrix/) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | تعداد [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) يحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخطي. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة _srcRect_ إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | عنصر [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى متوازي أضلاع مُعرّف بواسطة _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | عنصر [Matrix](/imaging/python-net/aspose.imaging/matrix/) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | تعداد [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) يحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخطي. |
| flatness | float | قيمة من 0 إلى 1 تحدد مدى تسطيح المسار الناتج. لمزيد من المعلومات، راجع طرق [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

يضيف مخططًا إضافيًا إلى المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | عنصر [Pen](/imaging/python-net/aspose.imaging/pen/) يحدد العرض بين المخطط الأصلي للمسار والمخطط الجديد الذي تُنشئه هذه الطريقة. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

يضيف مخططًا إضافيًا إلى [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | عنصر [Pen](/imaging/python-net/aspose.imaging/pen/) يحدد العرض بين المخطط الأصلي للمسار والمخطط الجديد الذي تُنشئه هذه الطريقة. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | عنصر [Matrix](/imaging/python-net/aspose.imaging/matrix/) يحدد تحويلًا لتطبيقه على المسار قبل توسيعه. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

يستبدل هذا [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | عنصر [Pen](/imaging/python-net/aspose.imaging/pen/) يحدد العرض بين المخطط الأصلي للمسار والمخطط الجديد الذي تُنشئه هذه الطريقة. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | عنصر [Matrix](/imaging/python-net/aspose.imaging/matrix/) يحدد تحويلًا لتطبيقه على المسار قبل توسيعه. |
| السطحية | float | قيمة تحدد مستوى التسطيح للمنحنيات. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# إنشاء كائن من تدفق ملف
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# تعيين المصدر للنسخة من ImageOptions
	tiffOptions.source = StreamSource(stream)
	# إنشاء نسخة من Image
	with Image.create(tiffOptions, 500, 500) as image:
		# إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		# مسح سطح Graphics.
		graphics.clear(Color.wheat);
		# إنشاء نسخة من الفئة GraphicsPath
		graphics_path = GraphicsPath()
		# إنشاء نسخة من الفئة Figure
		figure = Figure()
		# إضافة أشكال إلى كائن Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# إضافة كائن Figure إلى GraphicsPath
		graphics_path.add_figure(figure)
		# رسم المسار باستخدام كائن Pen باللون الأسود
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# احفظ جميع التغييرات.
		image.save()


```

### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#إنشاء نسخة من BmpOptions وتعيين خصائصه المتنوعة
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#إنشاء نسخة من FileCreateSource وتعيينها كمصدر للنسخة من BmpOptions
	#المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه IsTemporal أم لا
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#إنشاء مثيل من Image.
	with Image.create(bmpOptions, 500, 500) as image:
		# إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		# مسح سطح Graphics.
		graphics.clear(Color.wheat)
		# إنشاء نسخة من الفئة GraphicsPath
		graphicspath = GraphicsPath()
		#إنشاء نسخة من الفئة Figure
		figure1 = Figure()
		# إضافة شكل إلى كائن Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# إنشاء نسخة من الفئة Figure
		figure2 = Figure()
		# إضافة شكل إلى كائن Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# إضافة كائن Figure إلى GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# رسم المسار باستخدام كائن Pen باللون الأسود
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# احفظ جميع التغييرات.
		image.save()


```

