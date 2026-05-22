---
title: "Classe ColorPalette"
type: docs
weight: 1190
url: /fr/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Obtient un tableau de structures ARGB 32 bits. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Obtient un tableau de structures [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Obtient le nombre d'entrées. |
| is_compact_palette | bool | r | Obtient ou définit une valeur indiquant si une palette compacte est utilisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copie la palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copie la palette. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | Obtient la couleur de palette ARGB 32 bits par indice. |
| [get_color(index)](#get_color_index_8) | Obtient la couleur de la palette par indice. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | Obtient l'indice de la couleur la plus proche. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | Obtient l'indice de la couleur la plus proche. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | Obtient l'indice de la couleur la plus proche. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copie la palette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | La palette nouvellement créée et copiée ou null si une palette null est passée. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copie la palette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs. |
| use_compact_palette | bool | Indiquant si la palette est compacte. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | La palette nouvellement créée et copiée ou null si une palette null est passée. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les entrées de la palette de couleurs. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les entrées de la palette de couleurs. |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


```
 get_argb_32_color(index) 
```

Obtient la couleur de palette ARGB 32 bits par indice.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de couleur de la palette ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | L'entrée de la palette de couleurs spécifiée par le _index_. |


### Method: get_color(index) {#get_color_index_8}


```
 get_color(index) 
```

Obtient la couleur de la palette par indice.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de couleur de la palette. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | L'entrée de la palette de couleurs spécifiée par le _index_. |


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

Obtient l'indice de la couleur la plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_color | int | La couleur ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | L'index de la couleur la plus proche. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

Obtient l'indice de la couleur la plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_color | int | La couleur ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | L'index de la couleur la plus proche. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

Obtient l'indice de la couleur la plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | L'index de la couleur la plus proche. |


