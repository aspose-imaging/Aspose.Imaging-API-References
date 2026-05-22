---
title: "فئة LinearGradientBrush"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) باستخدام المعلمات الافتراضية.<br/>            اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة والمستطيل يقع في (0,0) بحجم (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| angle | float | r/w | يحصل أو يعيّن زاوية التدرج. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | يحصل أو يضبط [Blend](/imaging/python-net/aspose.imaging/blend/) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط لون التدرج النهائي. |
| gamma_correction | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | يحصل أو يعيّن [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| is_angle_scalable | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) يتغير أثناء التحويلات باستخدام هذا [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | يحصل على قيمة تشير إلى ما إذا كانت التحويلات قد تغيرت بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو<br/>            استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق مع الإصدارات السابقة من GDI+. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط ألوان التدرج الابتدائية والنهائية. |
| opacity | float | r/w | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة بالكامل. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يعيّن منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط لون التدرج الابتدائي. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن نسخة من [Matrix](/imaging/python-net/aspose.imaging/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | يحصل أو يعيّن تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) باستخدام النقاط والألوان المحددة. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) باستخدام النقاط والألوان المحددة. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
| [deep_clone()](#deep_clone__7) | ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة المحددة في البداية. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) وفقًا للترتيب المحدد. |
| reset_transform() | يعيد تعيين الخاصية [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) إلى هوية. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في الطرفين. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في الطرفين. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) باستخدام المعلمات الافتراضية.<br/>            اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة والمستطيل يقع في (0,0) بحجم (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | النقطة1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | النقطة2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | النقطة1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | النقطة2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون2. |
| angle | float | الزاوية. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون2. |
| angle | float | الزاوية. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون2. |
| angle | float | الزاوية. |
| is_angle_scalable | bool | إذا تم تعيينه إلى <c>true</c> [is angle scalable]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | اللون2. |
| angle | float | الزاوية. |
| is_angle_scalable | bool | إذا تم تعيينه إلى <c>true</c> [is angle scalable]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) باستخدام النقاط والألوان المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة البداية للانحدار الخطي. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة النهاية للانحدار الخطي. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون الابتدائي للتدرج الخطي. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون النهائي للتدرج الخطي. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) باستخدام النقاط والألوان المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل نقطة البداية للانحدار الخطي. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل نقطة النهاية للانحدار الخطي. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون الابتدائي للتدرج الخطي. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون النهائي للتدرج الخطي. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون النهائي للتدرج. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون النهائي للتدرج. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |
| is_angle_scalable | bool | إذا تم تعيينه إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون النهائي للتدرج. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

ينشئ مثيلًا جديدًا من الفئة [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | هيكل [Color](/imaging/python-net/aspose.imaging/color/) يمثل اللون النهائي للتدرج. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |
| is_angle_scalable | bool | إذا تم تعيينه إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| نوع | الوصف |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | فرشاة جديدة [Brush](/imaging/python-net/aspose.imaging/brush/) وهي النسخة العميقة من هذه الحالة من [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة المحددة في البداية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد الترتيب الذي يُضرب فيه المصفوفتان. |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد ما إذا كان يجب إضافة أو إلحاق مسبق لمصفوفة الدوران. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في الطرفين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في الطرفين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| المقياس | float | قيمة من 0 إلى 1 تحدد مدى سرعة تلاشي الألوان من اللون الابتدائي إلى _focus_ (اللون النهائي) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يختلط فيها اللون الابتدائي واللون النهائي بالتساوي). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| المقياس | float | قيمة من 0 إلى 1 تحدد مدى سرعة تلاشي الألوان من الـ _focus_. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


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

