---
title: "فئة ColorPalette"
type: docs
weight: 1190
url: /ar/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | يحصل على مصفوفة من هياكل ARGB 32-بت. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | يحصل على مصفوفة من هياكل [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | يحصل على عدد الإدخالات. |
| is_compact_palette | bool | r | يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | ينسخ لوحة الألوان. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | ينسخ لوحة الألوان. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [create_with_colors(entries)](#create_with_colors_entries_5) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | يحصل على لون لوحة الألوان ARGB 32-بت حسب الفهرس. |
| [get_color(index)](#get_color_index_8) | يحصل على لون لوحة الألوان حسب الفهرس. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | يحصل على فهرس أقرب لون. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | يحصل على فهرس أقرب لون. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | يحصل على فهرس أقرب لون. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_32_entries | int[] | إدخالات لوحة ألوان ARGB 32‑بت. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_32_entries | int[] | إدخالات لوحة ألوان ARGB 32‑بت. |
| is_compact_palette | bool | الإشارة إلى ما إذا كانت لوحة الألوان مدمجة. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | الإشارة إلى ما إذا كانت لوحة الألوان مدمجة. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

ينسخ لوحة الألوان.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | لوحة الألوان التي تم إنشاؤها ونسخها حديثًا أو null إذا تم تمرير لوحة ألوان null. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

ينسخ لوحة الألوان.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان. |
| use_compact_palette | bool | الإشارة إلى ما إذا كانت لوحة الألوان مدمجة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | لوحة الألوان التي تم إنشاؤها ونسخها حديثًا أو null إذا تم تمرير لوحة ألوان null. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_32_entries | int[] | إدخالات لوحة ألوان ARGB 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_32_entries | int[] | إدخالات لوحة ألوان ARGB 32‑بت. |
| is_compact_palette | bool | الإشارة إلى ما إذا كانت لوحة الألوان مدمجة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) وتكون الخاصية IsCompactPalette خاطئة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | إدخالات لوحة الألوان. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

ينشئ مثيلًا جديدًا من الفئة [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | إدخالات لوحة الألوان. |
| is_compact_palette | bool | الإشارة إلى ما إذا كانت لوحة الألوان مدمجة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


```
 get_argb_32_color(index) 
```

يحصل على لون لوحة الألوان ARGB 32-بت حسب الفهرس.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس لون لوحة ARGB 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | إدخال لوحة الألوان المحدد بواسطة _index_. |


### Method: get_color(index) {#get_color_index_8}


```
 get_color(index) 
```

يحصل على لون لوحة الألوان حسب الفهرس.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس لون لوحة الألوان. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | إدخال لوحة الألوان المحدد بواسطة _index_. |


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

يحصل على فهرس أقرب لون.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_32_color | int | لون ARGB 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

يحصل على فهرس أقرب لون.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_32_color | int | لون ARGB 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

يحصل على فهرس أقرب لون.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


