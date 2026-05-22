---
title: "فئة Matrix"
type: docs
weight: 6070
url: /ar/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Matrix()](#Matrix__1) | ينشئ نسخة جديدة من فئة Matrix كمصفوفة هوية. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | ينشئ نسخة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | تشير هذه البتة flag إلى أن التحويل المحدد بهذا الكائن<br/> يقوم بقلب صورة مرآة حول محور ما مما يغيّر نظام الإحداثيات اليدوي الأيمن المعتاد إلى نظام يدوي أيسر<br/> بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى.<br/> نظام الإحداثيات اليدوي الأيمن هو ذلك الذي يدور فيه المحور X الموجب عكس اتجاه عقارب الساعة ليطابق المحور Y الموجب مشابهًا لاتجاه انحناء أصابع يدك اليمنى عندما تنظر مباشرة إلى إبهامك.<br/> نظام الإحداثيات اليدوي الأيسر هو ذلك الذي يدور فيه المحور X الموجب مع اتجاه عقارب الساعة ليطابق المحور Y الموجب مشابهًا لاتجاه انحناء أصابع يدك اليسرى.<br/> لا توجد طريقة رياضية لتحديد زاوية القلب أو الانعكاس الأصلي لأن جميع زوايا القلب متطابقة عند تطبيق دوران تعديل مناسب.<br/> ملاحظة: تم إضافة TypeFlip بعد أن كان GENERAL_TRANSFORM متاحًا للجمهور<br/> ولم يعد من الممكن إعادة ترقيم بتات flag بسهولة دون إدخال عدم توافق ثنائي في الشيفرة الخارجية. |
| TYPE_GENERAL_ROTATION [static] | int | r | تشير هذه البتة flag إلى أن التحويل المحدد بهذا الكائن<br/> يقوم بدوران بزاوية عشوائية بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى.<br/> يغيّر الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه.<br/> هذه البتة flag لا يمكن استخدامها مع الـ |
| TYPE_GENERAL_SCALE [static] | int | r | يقوم المقياس العام بضرب طول المتجهات بمقادير مختلفة<br/> في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة.<br/> هذه البتة flag لا يمكن استخدامها مع علم TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | تشير هذه الثابتة إلى أن التحويل المحدد بهذا الكائن<br/> يقوم بتحويل تعسفي لإحداثيات الإدخال.<br/> إذا كان يمكن تصنيف هذا التحويل بأي من الثوابت المذكورة أعلاه، سيكون النوع إما الثابتة TypeIdentity أو<br/> مجموعة من بتات flag المناسبة لمختلف التحويلات الإحداثية التي يقوم بها هذا التحويل. |
| TYPE_IDENTITY [static] | int | r | تحويل الهوية هو التحويل الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال.<br/> إذا كان هذا التحويل أي شيء غير تحويل الهوية، سيكون النوع إما الثابتة GENERAL_TRANSFORM أو<br/> مجموعة من بتات flag المناسبة لمختلف التحويلات الإحداثية التي يقوم بها هذا التحويل. |
| TYPE_MASK_ROTATION [static] | int | r | هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالدوران. |
| TYPE_MASK_SCALE [static] | int | r | هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالمقياس. |
| TYPE_QUADRANT_ROTATION [static] | int | r | تشير هذه البتة flag إلى أن التحويل المحدد بهذا الكائن<br/> يقوم بدوران ربعي بضعف من 90 درجة<br/> بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى.<br/> يغيّر الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه.<br/> هذه البتة flag لا يمكن استخدامها مع علم TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | الترجمة تحرك الإحداثيات بمقدار ثابت في x<br/> و y دون تغيير طول المتجه أو زاويته. |
| TYPE_UNIFORM_SCALE [static] | int | r | المقياس المتجانس يضاعف طول المتجهات بنفس المقدار في كل من اتجاهي x و y دون تغيير الزاوية بين المتجهات.<br/> هذه البتة flag لا يمكن استخدامها مع علم TypeGeneralScale. |
| elements | float[] | r | يحصل على مصفوفة من القيم العائمة التي تمثل عناصر هذا [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| m11 | float | r | يحصل على عنصر المصفوفة في الصف الأول العمود الأول. يمثل المقياس على المحور X. |
| m12 | float | r | يحصل على عنصر المصفوفة في الصف الأول العمود الثاني. يمثل القص على المحور Y. |
| m21 | float | r | يحصل على عنصر المصفوفة في الصف الثاني العمود الأول. يمثل القص على المحور X. |
| m22 | float | r | يحصل على عنصر المصفوفة في الصف الثاني العمود الثاني. يمثل التحجيم على المحور Y. |
| m31 | float | r | يحصل على عنصر المصفوفة في الصف الثالث العمود الأول. يمثل الإزاحة على المحور X. |
| m32 | float | r | يحصل على عنصر المصفوفة في الصف الثالث العمود الأول. يمثل الإزاحة على المحور Y. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط. |
| [get_elements()](#get_elements__3) | يحصل على نسخة من عناصر المصفوفة. |
| [multiply(t_tx)](#multiply_t_tx_4) | يضرب هذه Matrix بالمصفوفة المحددة في معلمة matrix باستخدام ترتيب (Prepend) الافتراضي. |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | يضرب هذه Matrix بالمصفوفة المحددة في معلمة matrix، وبالترتيب المحدد في معلمة order. |
| reset() | يعيد تعيين هذه Matrix لتحتوي على عناصر مصفوفة الهوية. |
| [rotate(angle)](#rotate_angle_6) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معلمة angle، حول الأصل (إحداثيات x و y الصفرية) لهذه Matrix بالترتيب الافتراضي (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_7) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معلمة angle، حول الأصل (إحداثيات x و y الصفرية) لهذه Matrix بالترتيب المحدد. |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب الافتراضي (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب المحدد. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه [Matrix](/imaging/python-net/aspose.imaging/matrix/) باستخدام الترتيب المحدد. |
| [scale(sx, sy)](#scale_sx_sy_11) | يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه Matrix باستخدام ترتيب (Prepend) الافتراضي. |
| [transform_points(points)](#transform_points_points_12) | يطبق التحويل الهندسي المُمَثَّل بهذه [Matrix](/imaging/python-net/aspose.imaging/matrix/) على مصفوفة محددة من النقاط. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | يطبق متجه الإزاحة المحدد على هذه Matrix بالترتيب المحدد. |
| [translate(tx, ty)](#translate_tx_ty_14) | يطبق متجه الإزاحة المحدد على هذه [Matrix](/imaging/python-net/aspose.imaging/matrix/) باستخدام ترتيب (Prepend) الافتراضي. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

ينشئ نسخة جديدة من فئة Matrix كمصفوفة هوية.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| m11 | float | m00     M11     تحجيم X |
| m12 | float | m10     M12     قص Y |
| m21 | float | m01     M21     قص X |
| m22 | float | m11     M22     تحجيم Y |
| m31 | float | m02     M31     إزاحة X |
| m32 | float | m12     M32     ترجمة Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

ينشئ نسخة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | مصفوفة أساسية للمعالجة |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاثة هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل إليه. الزاوية السفلية اليمنى لمتوازي الأضلاع مفترضة بناءً على الزوايا الثلاث الأولى. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاثة هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل إليه. الزاوية السفلية اليمنى لمتوازي الأضلاع مفترضة بناءً على الزوايا الثلاث الأولى. |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاثة هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل إليه. الزاوية السفلية اليمنى لمتوازي الأضلاع مفترضة بناءً على الزوايا الثلاث الأولى. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

ينشئ نسخة جديدة من فئة [Matrix](/imaging/python-net/aspose.imaging/matrix/) للتحويل الهندسي المحدد بالمستطيل المحدد ومجموعة النقاط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاثة هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل إليه. الزاوية السفلية اليمنى لمتوازي الأضلاع مفترضة بناءً على الزوايا الثلاث الأولى. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

يحصل على نسخة من عناصر المصفوفة.

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] | نسخة عناصر المصفوفة. |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

يضرب هذه Matrix بالمصفوفة المحددة في معلمة matrix باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي سيتم الضرب معها. |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

يضرب هذه Matrix بالمصفوفة المحددة في معلمة matrix، وبالترتيب المحدد في معلمة order.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | القيمة tx. القيمة tx. القيمة tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب. الترتيب. الترتيب. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معلمة angle، حول الأصل (إحداثيات x و y الصفرية) لهذه Matrix بالترتيب الافتراضي (Prepend).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معلمة angle، حول الأصل (إحداثيات x و y الصفرية) لهذه Matrix بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | ترتيب المصفوفة. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب الافتراضي (Prepend).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | الزاوية. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | النقطة. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | الزاوية. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | النقطة. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه [Matrix](/imaging/python-net/aspose.imaging/matrix/) باستخدام الترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scale_x | float | المقياس X. |
| scale_y | float | المقياس Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب. |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه Matrix باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | القيمة sx. القيمة sx. القيمة sx. |
| sy | float | القيمة sy. القيمة sy. القيمة sy. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

يطبق التحويل الهندسي المُمَثَّل بهذه [Matrix](/imaging/python-net/aspose.imaging/matrix/) على مصفوفة محددة من النقاط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | النقاط. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

يطبق متجه الإزاحة المحدد على هذه Matrix بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| offset_x | float | الإزاحة X. |
| offset_y | float | الإزاحة Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب. |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

يطبق متجه الإزاحة المحدد على هذه [Matrix](/imaging/python-net/aspose.imaging/matrix/) باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tx | float | القيمة tx. القيمة tx. القيمة tx. |
| ty | float | القيمة ty. القيمة ty. القيمة ty. |

