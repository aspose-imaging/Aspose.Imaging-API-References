---
title: "الفئة PathMulticolorGradientBrush"
type: docs
weight: 70
url: /ar/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_2) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_3) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_4) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_5) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | يسترجع أو يعيّن نقطة المركز لتدرج المسار. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | يسترجع أو يعيّن نقطة التركيز لتلاشي التدرج. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | يسترجع مسار الرسومات الذي بُني عليه هذا الفرش. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | يحصل أو يعيّن [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| is_transform_changed | bool | r | يحصل على قيمة تشير إلى ما إذا كانت التحويلات قد تغيرت بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو<br/>            استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق مع الإصدارات السابقة من GDI+. |
| opacity | float | r/w | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة بالكامل. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | يسترجع نقاط المسار التي بُني عليها هذا الفرش. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن نسخة من [Matrix](/imaging/python-net/aspose.imaging/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | يحصل أو يعيّن تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالمسار المحدد. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف. |
| [deep_clone()](#deep_clone__6) | ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة المحددة في البداية. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) وفقًا للترتيب المحدد. |
| reset_transform() | يعيد تعيين الخاصية [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) إلى هوية. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_13) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_14) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_2}


```
 PathMulticolorGradientBrush(path_points) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تشكل رؤوس المسار. |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_3}


```
 PathMulticolorGradientBrush(path_points) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تشكل رؤوس المسار. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تشكل رؤوس المسار. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | قائمة [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) التي تحدد كيفية تجانب التعبئات المرسومة بهذه [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تشكل رؤوس المسار. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | قائمة [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) التي تحدد كيفية تجانب التعبئات المرسومة بهذه [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالمسار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) الذي يحدد المنطقة المملوءة بهذه [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تشكل رؤوس المسار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل النقاط التي تشكل رؤوس المسار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تشكل رؤوس المسار. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | قائمة [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) التي تحدد كيفية تجانب التعبئات المرسومة بهذه [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

ينشئ مثيلاً جديداً من الفئة [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل النقاط التي تشكل رؤوس المسار. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | قائمة [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) التي تحدد كيفية تجانب التعبئات المرسومة بهذه [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| نوع | الوصف |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | فرشاة جديدة [Brush](/imaging/python-net/aspose.imaging/brush/) وهي النسخة العميقة من هذه الحالة من [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة المحددة في البداية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد الترتيب الذي يُضرب فيه المصفوفتان. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد ما إذا كان يجب إضافة أو إلحاق مسبق لمصفوفة الدوران. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


```
 scale_transform(sx, sy, order) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | قائمة [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) التي تحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التحجيم. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_13}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_14}


```
 translate_transform(dx, dy, order) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب (إلحاق مسبق أو إلحاق) الذي يتم تطبيق الإزاحة به. |

