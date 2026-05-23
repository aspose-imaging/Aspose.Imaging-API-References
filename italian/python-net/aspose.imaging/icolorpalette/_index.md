---
title: "IColorPalette Classe"
type: docs
weight: 5210
url: /it/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Restituisce un array di strutture ARGB a 32 bit. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Restituisce un array di strutture [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Restituisce il conteggio delle voci. |
| is_compact_palette | bool | r | Restituisce un valore che indica se viene utilizzata una palette compatta. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Restituisce il colore della palette ARGB a 32 bit per indice. |
| [get_color(index)](#get_color_index_2) | Restituisce il colore della palette per indice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Restituisce l'indice del colore ARGB a 32 bit più vicino. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Restituisce l'indice del colore ARGB a 32 bit più vicino. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

Restituisce il colore della palette ARGB a 32 bit per indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del colore della tavolozza ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La voce della tavolozza dei colori specificata dall'_index_'. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

Restituisce il colore della palette per indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del colore della tavolozza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | La voce della tavolozza dei colori specificata dall'_index_'. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Restituisce l'indice del colore ARGB a 32 bit più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_color | int | Il colore ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice del colore più vicino. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Restituisce l'indice del colore ARGB a 32 bit più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice del colore più vicino. |


