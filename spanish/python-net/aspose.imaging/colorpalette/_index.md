---
title: "Clase ColorPalette"
type: docs
weight: 1190
url: /es/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Obtiene una matriz de estructuras ARGB de 32 bits. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Obtiene una matriz de estructuras [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Obtiene el recuento de entradas. |
| is_compact_palette | bool | r | Obtiene o establece un valor que indica si se usa una paleta compacta. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copia la paleta. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copia la paleta. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [get_color(index)](#get_color_index_8) | Obtiene el color de la paleta por índice. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | Obtiene el índice del color más cercano. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | Obtiene el índice del color más cercano. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | Obtiene el índice del color más cercano. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |
| is_compact_palette | bool | Indica si la paleta es compacta. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Indica si la paleta es compacta. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copia la paleta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | La paleta recién creada y copiada o null si se pasa una paleta null. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copia la paleta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores. |
| use_compact_palette | bool | Indica si la paleta es compacta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | La paleta recién creada y copiada o null si se pasa una paleta null. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |
| is_compact_palette | bool | Indica si la paleta es compacta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Las entradas de la paleta de colores. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Las entradas de la paleta de colores. |
| is_compact_palette | bool | Indica si la paleta es compacta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


```
 get_argb_32_color(index) 
```

Obtiene el color de la paleta ARGB de 32 bits por índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de color de la paleta ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La entrada de la paleta de colores especificada por el _index_. |


### Method: get_color(index) {#get_color_index_8}


```
 get_color(index) 
```

Obtiene el color de la paleta por índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de color de la paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | La entrada de la paleta de colores especificada por el _index_. |


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

Obtiene el índice del color más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_color | int | El color ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

Obtiene el índice del color más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_color | int | El color ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

Obtiene el índice del color más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |


