---
title: "IColorPalette فئة"
type: docs
weight: 5210
url: /ar/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | يحصل على مصفوفة من هياكل ARGB 32-بت. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | يحصل على مصفوفة من هياكل [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | يحصل على عدد الإدخالات. |
| is_compact_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | يحصل على لون لوحة الألوان ARGB 32-بت حسب الفهرس. |
| [get_color(index)](#get_color_index_2) | يحصل على لون لوحة الألوان حسب الفهرس. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | يحصل على فهرس أقرب لون ARGB 32‑بت. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | يحصل على فهرس أقرب لون ARGB 32‑بت. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

يحصل على فهرس أقرب لون ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_32_color | int | لون ARGB 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

يحصل على فهرس أقرب لون ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


