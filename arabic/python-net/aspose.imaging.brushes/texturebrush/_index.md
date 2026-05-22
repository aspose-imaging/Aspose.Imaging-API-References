---
title: "الفئة TextureBrush"
type: docs
weight: 90
url: /ar/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | يسترجع كائن [Image](/imaging/python-net/aspose.imaging/image/) المرتبط بهذا كائن [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | يسترجع [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/) المرتبط بهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) المرتبط بهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| is_transform_changed | bool | r | يحصل على قيمة تشير إلى ما إذا كانت التحويلات قد تغيرت بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو<br/>            استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق مع الإصدارات السابقة من GDI+. |
| opacity | float | r/w | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة بالكامل. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن نسخة من [Matrix](/imaging/python-net/aspose.imaging/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | يحصل أو يعيّن تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة ووضع الالتفاف. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [deep_clone()](#deep_clone__8) | ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة المحددة في البداية. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) وفقًا للترتيب المحدد. |
| reset_transform() | يعيد تعيين الخاصية [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) إلى هوية. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | كائن [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) يحتوي على معلومات إضافية حول الصورة المستخدمة من قبل هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | كائن [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) يحتوي على معلومات إضافية حول الصورة المستخدمة من قبل هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة ووضع الالتفاف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية تجانب هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية تجانب هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية تجانب هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | كائن [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) يحتوي على معلومات إضافية حول الصورة المستخدمة من قبل هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | كائن [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) يحتوي على معلومات إضافية حول الصورة المستخدمة من قبل هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة ووضع الالتفاف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية تجانب هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية تجانب هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | كائن [Image](/imaging/python-net/aspose.imaging/image/) الذي يستخدمه هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | تعداد [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية تجانب هذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| نوع | الوصف |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | فرشاة جديدة [Brush](/imaging/python-net/aspose.imaging/brush/) وهي النسخة العميقة من هذه الحالة من [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة المحددة في البداية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

يضرب الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد الترتيب الذي يُضرب فيه المصفوفتان. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد ما إذا كان يجب إضافة أو إلحاق مسبق لمصفوفة الدوران. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


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

