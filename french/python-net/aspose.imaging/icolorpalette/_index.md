---
title: "Classe IColorPalette"
type: docs
weight: 5210
url: /fr/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Obtient un tableau de structures ARGB 32 bits. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Obtient un tableau de structures [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Obtient le nombre d'entrées. |
| is_compact_palette | bool | r | Obtient une valeur indiquant si une palette compacte est utilisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Obtient la couleur de palette ARGB 32 bits par indice. |
| [get_color(index)](#get_color_index_2) | Obtient la couleur de la palette par indice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Obtient l'index de la couleur ARGB 32 bits la plus proche. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Obtient l'index de la couleur ARGB 32 bits la plus proche. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Obtient l'index de la couleur ARGB 32 bits la plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_color | int | La couleur ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | L'index de la couleur la plus proche. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Obtient l'index de la couleur ARGB 32 bits la plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | L'index de la couleur la plus proche. |


