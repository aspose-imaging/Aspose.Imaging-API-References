---
title: "الفئة ColorPaletteHelper"
type: docs
weight: 1200
url: /ar/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | ينشئ لوحة ألوان 4 بت. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | ينشئ لوحة تدرج رمادي 4 بت. |
| [create_8_bit()](#create_8_bit__3) | ينشئ لوحة ألوان 8 بت. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | ينشئ لوحة تدرج رمادي 8 بت. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | يحصل على لوحة الألوان الرمادية للعدد المحدد من البتات. القيم المسموح بها للبت هي 1، 2، 4، 8. |
| [create_monochrome()](#create_monochrome__6) | ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. سيتم تحسين اللوحة للحصول على جودة صورة مفهرسة أفضل أو تُؤخذ "كما هي" عندما يتم استخدام PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. سيتم تحسين اللوحة للحصول على جودة صورة مفهرسة أفضل أو تُؤخذ "كما هي" عندما يتم استخدام PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | احصل على لوحة ألوان مكوّنة من 256 لونًا، مُستمدة من البتات العليا لقيم ألوان الصورة الأولية. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | احصل على لوحة ألوان موحدة مكوّنة من 256 لونًا. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | يحدد ما إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

ينشئ لوحة ألوان 4 بت.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان ذات 4 بت. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

ينشئ لوحة تدرج رمادي 4 بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| min_is_white | bool | إذا تم تعيينه إلى <c>true</c> تبدأ اللوحة باللون الأبيض، وإلا تبدأ باللون الأسود. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان الرمادية ذات 4 بت. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

ينشئ لوحة ألوان 8 بت.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان ذات 8 بت. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

ينشئ لوحة تدرج رمادي 8 بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| min_is_white | bool | إذا تم تعيينه إلى <c>true</c> تبدأ اللوحة باللون الأبيض، وإلا تبدأ باللون الأسود. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان الرمادية ذات 8 بت. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

يحصل على لوحة الألوان الرمادية للعدد المحدد من البتات. القيم المسموح بها للبت هي 1، 2، 4، 8.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| بتات | int | عدد البتات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة ألوان رمادية. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة ألوان للصور أحادية اللون. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود الصورة الوجهة. |
| entries_count | int | عدد الإدخالات المطلوب. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود الصورة الوجهة. |
| entries_count | int | عدد الإدخالات المطلوب. |
| use_image_palette | bool | إذا تم تعيينه، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متاحة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود الصورة الوجهة. |
| entries_count | int | عدد الإدخالات المطلوب. |
| use_image_palette | bool | إذا تم تعيينه، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متاحة. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون الذي يجب استخدامه كلون خلفية لاستبدال ألفا شبه الشفاف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود الصورة الوجهة. |
| entries_count | int | عدد الإدخالات المطلوب. |
| use_image_palette | bool | إذا تم تعيينه، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متاحة. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون الذي يجب استخدامه كلون خلفية لاستبدال ألفا شبه الشفاف. |
| keep_transparency | bool | إذا تم التعيين، فستأخذ في الاعتبار بتات قناة ألفا لألوان الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| entries_count | int | عدد الإدخالات المطلوب. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. سيتم تحسين اللوحة للحصول على جودة صورة مفهرسة أفضل أو تُؤخذ "كما هي" عندما يتم استخدام PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| entries_count | int | عدد الإدخالات المطلوب. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | طريقة استخراج اللوحة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. سيتم تحسين اللوحة للحصول على جودة صورة مفهرسة أفضل أو تُؤخذ "كما هي" عندما يتم استخدام PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| entries_count | int | عدد الإدخالات المطلوب. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | طريقة استخراج اللوحة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود الصورة الوجهة. |
| entries_count | int | عدد الإدخالات المطلوب. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

يحصل على لوحة ألوان من الصورة النقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| entries_count | int | عدد الإدخالات المطلوب. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من الـ _image_ وتحتوي على _entriesCount_ إدخال. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

احصل على لوحة ألوان مكوّنة من 256 لونًا، مُستمدة من البتات العليا لقيم ألوان الصورة الأولية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | الـ [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

احصل على لوحة ألوان موحدة مكوّنة من 256 لونًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | الـ [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

يحدد ما إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | اللوحة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كانت اللوحة المحددة تحتوي على ألوان شفافة؛ وإلا، <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# إنشاء صورة BMP بحجم 100 × 100 بكسل.
with BmpImage(100, 100) as bmpImage:
	# التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# املأ الصورة بالكامل بفرشاة التدرج الخطي.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# احصل على أقرب لوحة ألوان 8‑بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملونة باللوحة
	# تقريبًا لا يمكن تمييزها بصريًا عن صورة BMP بدون لوحة ألوان
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# لوحة ألوان 8‑بت تحتوي على حد أقصى 256 لونًا.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# المخرجات تبدو هكذا:
# حجم الصورة مع اللوحة هو 11078 بايت.
# حجم الصورة بدون لوحة هو 40054 بايت.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# يحمّل صورة PNG        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# استخدم نوع اللون المفهرس
	png_options.color_type = PngColorType.INDEXED_COLOR
	# استخدم أقصى ضغط
	png_options.compression_level = 9
	# احصل على أقرب لوحة ألوان 8‑بت، تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة
	# مع لوحة ألوان تقريبًا لا يمكن تمييزها بصريًا عن صورة بدون لوحة ألوان.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# يجب تقليل حجم ملف الإخراج بشكل كبير

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# إنشاء BmpOptions
	saveOptions = BmpOptions()

	# استخدم 8 بتات لكل بكسل لتقليل حجم الصورة الناتجة.
	saveOptions.bits_per_pixel = 8

	# عيّن أقرب لوحة ألوان 8‑بت تغطي الحد الأقصى لعدد بكسلات الصورة، بحيث تكون الصورة الملونة باللوحة
	# يكاد يكون غير قابل للتمييز بصريًا عن نسخة غير مُلوَّنة.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# احفظ دون ضغط.
	# يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
	saveOptions.compression = BitmapCompression.RGB

	# عيّن الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

