---
title: "فئة ImageAttributes"
type: docs
weight: 5660
url: /ar/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | يُنشئ مثيلاً جديداً للفئة [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| clear_brush_remap_table() | يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| clear_color_key() | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [clear_color_key(type)](#clear_color_key_type_1) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| clear_color_matrix() | يمسح مصفوفة تعديل اللون للفئة الافتراضية. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | يمسح مصفوفة تعديل اللون لفئة محددة. |
| clear_gamma() | يعطل تصحيح جاما للفئة الافتراضية. |
| [clear_gamma(type)](#clear_gamma_type_3) | يعطل تصحيح جاما لفئة محددة. |
| clear_no_op() | يمسح إعداد NoOp للفئة الافتراضية. |
| [clear_no_op(type)](#clear_no_op_type_4) | يمسح إعداد NoOp لفئة محددة. |
| clear_output_channel() | يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| clear_output_channel_color_profile() | يمسح إعداد ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة. |
| clear_remap_table() | يمسح جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | يمسح جدول إعادة تعيين الألوان لفئة محددة. |
| clear_threshold() | يمسح قيمة العتبة للفئة الافتراضية. |
| [clear_threshold(type)](#clear_threshold_type_8) | يمسح قيمة العتبة لفئة محددة. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | يضبط جدول إعادة تعيين اللون لفئة الفرشاة. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | يضبط مفتاح اللون للفئة الافتراضية. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | يضبط مصفوفة تعديل اللون لفئة محددة. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | يضبط قيمة غاما للفئة الافتراضية. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | يضبط قيمة غاما لفئة محددة. |
| set_no_op() | يعطل تعديل اللون للفئة الافتراضية. |
| [set_no_op(type)](#set_no_op_type_20) | يعطل تعديل اللون لفئة محددة. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | يضبط ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | يضبط ملف تعريف لون قناة الإخراج لفئة محددة. |
| [set_remap_table(map)](#set_remap_table_map_25) | يضبط جدول إعادة تعيين اللون للفئة الافتراضية. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | يضبط جدول إعادة تعيين اللون لفئة محددة. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | يضبط العتبة (نطاق الشفافية) للفئة الافتراضية. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | يضبط العتبة (نطاق الشفافية) لفئة محددة. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

يُنشئ مثيلاً جديداً للفئة [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/).

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم مسح مفتاح اللون لها. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

يمسح مصفوفة تعديل اللون لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم مسح مصفوفة تعديل اللون لها. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

يعطل تصحيح جاما لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم تعطيل تصحيح غاما لها. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

يمسح إعداد NoOp لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم مسح إعداد NoOp لها. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم مسح إعداد قناة الإخراج لها. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم مسح إعداد ملف تعريف قناة الإخراج لها. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

يمسح جدول إعادة تعيين الألوان لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم مسح جدول إعادة التعيين لها. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

يمسح قيمة العتبة لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم مسح العتبة لها. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

يضبط جدول إعادة تعيين اللون لفئة الفرشاة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | مصفوفة من كائنات [ColorMap](/imaging/python-net/aspose.imaging/colormap/). |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

يضبط مفتاح اللون للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | قيمة مفتاح اللون المنخفض. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | قيمة مفتاح اللون العالي. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | قيمة مفتاح اللون المنخفض. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | قيمة مفتاح اللون العالي. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم تعيين مفتاح اللون لها. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل اللون. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل التدرج الرمادي. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل اللون. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل التدرج الرمادي. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | عنصر من [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل اللون. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل التدرج الرمادي. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | عنصر من [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم تعيين مصفوفات تعديل اللون وتعديل التدرج الرمادي لها. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل اللون. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل اللون. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | عنصر من [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفة تعديل اللون. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

يضبط مصفوفة تعديل اللون لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | مصفوفة تعديل اللون. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | عنصر من [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفة تعديل اللون. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم تعيين مصفوفة تعديل اللون لها. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

يضبط قيمة غاما للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| جاما | float | قيمة تصحيح جاما. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

يضبط قيمة غاما لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| جاما | float | قيمة تصحيح جاما. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من تعداد [ColorAdjustType] يحدد الفئة التي يتم تعيين قيمة جاما لها. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

يعطل تعديل اللون لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم إيقاف تصحيح اللون لها. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | عنصر من [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) يحدد قناة الإخراج. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | عنصر من [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) يحدد قناة الإخراج. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم تعيين قناة الإخراج لها. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

يضبط ملف تعريف لون قناة الإخراج للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color_profile_filename | string | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\System32\Spool\Drivers\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار الكامل. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

يضبط ملف تعريف لون قناة الإخراج لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color_profile_filename | string | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\System32\Spool\Drivers\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار الكامل. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم تعيين ملف تعريف لون قناة الإخراج لها. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

يضبط جدول إعادة تعيين اللون للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | مصفوفة من أزواج الألوان من النوع [ColorMap](/imaging/python-net/aspose.imaging/colormap/). كل زوج ألوان يحتوي على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

يضبط جدول إعادة تعيين اللون لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | مصفوفة من أزواج الألوان من النوع [ColorMap](/imaging/python-net/aspose.imaging/colormap/). كل زوج ألوان يحتوي على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم تعيين جدول إعادة تعيين اللون لها. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

يضبط العتبة (نطاق الشفافية) للفئة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحدّ | float | رقم حقيقي يحدد قيمة العتبة. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

يضبط العتبة (نطاق الشفافية) لفئة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحدّ | float | قيمة عتبة من 0.0 إلى 1.0 تُستخدم كنقطة توقف لفرز الألوان التي سيتم ربطها إما بقيمة قصوى أو قيمة دنيا. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | عنصر من [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) يحدد الفئة التي يتم فيها تعيين عتبة اللون. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

يضبط وضع الالتفاف المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | عنصر من [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية استخدام نسخ مكررة من الصورة لتغطية منطقة. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | عنصر من [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية استخدام نسخ مكررة من الصورة لتغطية منطقة. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | كائن [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) يحدد لون البكسلات خارج الصورة المُرَسَمة. يكون هذا اللون مرئياً إذا تم ضبط معامل الوضع على [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | عنصر من [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) يحدد كيفية استخدام نسخ مكررة من الصورة لتغطية منطقة. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | كائن لون يحدد لون البكسلات خارج الصورة المُرَسَمة. يكون هذا اللون مرئياً إذا تم ضبط معامل الوضع على [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |
| قفل | bool | هذا المعامل لا يؤثر. اضبطه على false. |

