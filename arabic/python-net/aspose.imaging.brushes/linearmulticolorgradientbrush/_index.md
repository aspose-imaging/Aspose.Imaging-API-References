---
title: "فئة LinearMulticolorGradientBrush"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام المعلمات الافتراضية.<br/>            اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة، والمستطيل يقع في (0,0) بحجم (1,1). |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| angle | float | r/w | يحصل أو يعيّن زاوية التدرج. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| gamma_correction | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | يحصل أو يعيّن [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| is_angle_scalable | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) يتغير أثناء التحويلات باستخدام هذا [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | يحصل على قيمة تشير إلى ما إذا كانت التحويلات قد تغيرت بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو<br/>            استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق مع الإصدارات السابقة من GDI+. |
| opacity | float | r/w | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة بالكامل. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يعيّن منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن نسخة من [Matrix](/imaging/python-net/aspose.imaging/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | يحصل أو يعيّن تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_points(point1, point2)](#create_with_points_point1_point2_1) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة. |
| [create_with_points_f(point1, point2)](#create_with_points_f_point1_point2_2) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة. |
| [create_with_rect(rect, angle)](#create_with_rect_rect_angle_3) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [create_with_rect_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [create_with_rect_f(rect, angle)](#create_with_rect_f_rect_angle_5) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6) | يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [deep_clone()](#deep_clone__7) | ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة المحددة في البداية. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) وفقًا للترتيب المحدد. |
| reset_transform() | يعيد تعيين الخاصية [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) إلى هوية. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_14) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_15) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام المعلمات الافتراضية.<br/>            اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة، والمستطيل يقع في (0,0) بحجم (1,1).

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة البداية للانحدار الخطي. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة النهاية للانحدار الخطي. |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة البداية للانحدار الخطي. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة النهاية للانحدار الخطي. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |
| is_angle_scalable | bool | إذا تم تعيينها إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |
| is_angle_scalable | bool | إذا تم تعيينها إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

### Method: create_with_points(point1, point2)  [static] {#create_with_points_point1_point2_1}


```
 create_with_points(point1, point2) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة البداية للانحدار الخطي. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) يمثل نقطة النهاية للانحدار الخطي. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_points_f(point1, point2)  [static] {#create_with_points_f_point1_point2_2}


```
 create_with_points_f(point1, point2) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) باستخدام النقاط المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل نقطة البداية للانحدار الخطي. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) يمثل نقطة النهاية للانحدار الخطي. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect(rect, angle)  [static] {#create_with_rect_rect_angle_3}


```
 create_with_rect(rect, angle) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4}


```
 create_with_rect_angle_scalable(rect, angle, is_angle_scalable) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |
| is_angle_scalable | bool | إذا تم تعيينها إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f(rect, angle)  [static] {#create_with_rect_f_rect_angle_5}


```
 create_with_rect_f(rect, angle) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6}


```
 create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable) 
```

يُنشئ مثيلاً جديدًا من الفئة [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يحدد حدود الانحدار الخطي. |
| angle | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه الانحدار. |
| is_angle_scalable | bool | إذا تم تعيينها إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_14}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_15}


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

