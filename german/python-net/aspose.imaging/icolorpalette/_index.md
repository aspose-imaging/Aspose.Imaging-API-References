---
title: "IColorPalette Klasse"
type: docs
weight: 5210
url: /de/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Gibt ein Array von 32‑Bit‑ARGB‑Strukturen zurück. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Gibt ein Array von [Color](/imaging/python-net/aspose.imaging/color/) Strukturen zurück. |
| entries_count | int | r | Gibt die Anzahl der Einträge zurück. |
| is_compact_palette | bool | r | Ermittelt einen Wert, der angibt, ob eine kompakte Palette verwendet wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Gibt die 32‑Bit‑ARGB‑Palettenfarbe nach Index zurück. |
| [get_color(index)](#get_color_index_2) | Gibt die Palettenfarbe nach Index zurück. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Ermittelt den Index der nächstgelegenen 32-Bit-ARGB-Farbe. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Ermittelt den Index der nächstgelegenen 32-Bit-ARGB-Farbe. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

Gibt die 32‑Bit‑ARGB‑Palettenfarbe nach Index zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der 32‑Bit‑ARGB‑Palettenfarbindex. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Farbpaletteneintrag, der durch den _index_ angegeben ist. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

Gibt die Palettenfarbe nach Index zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Palettenfarbindex. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Der Farbpaletteneintrag, der durch den _index_ angegeben ist. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Ermittelt den Index der nächstgelegenen 32-Bit-ARGB-Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Ermittelt den Index der nächstgelegenen 32-Bit-ARGB-Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


