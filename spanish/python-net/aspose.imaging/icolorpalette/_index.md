---
title: "Clase IColorPalette"
type: docs
weight: 5210
url: /es/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Obtiene una matriz de estructuras ARGB de 32 bits. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Obtiene una matriz de estructuras [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Obtiene el recuento de entradas. |
| is_compact_palette | bool | r | Obtiene un valor que indica si se usa una paleta compacta. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [get_color(index)](#get_color_index_2) | Obtiene el color de la paleta por índice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Obtiene el índice del color ARGB de 32 bits más cercano. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Obtiene el índice del color ARGB de 32 bits más cercano. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Obtiene el índice del color ARGB de 32 bits más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_color | int | El color ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Obtiene el índice del color ARGB de 32 bits más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |


