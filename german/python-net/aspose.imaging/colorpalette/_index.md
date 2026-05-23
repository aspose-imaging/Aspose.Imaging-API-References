---
title: "ColorPalette Klasse"
type: docs
weight: 1190
url: /de/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Gibt ein Array von 32‑Bit‑ARGB‑Strukturen zurück. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Gibt ein Array von [Color](/imaging/python-net/aspose.imaging/color/) Strukturen zurück. |
| entries_count | int | r | Gibt die Anzahl der Einträge zurück. |
| is_compact_palette | bool | r | Liest oder setzt einen Wert, der angibt, ob eine kompakte Palette verwendet wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopiert die Palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopiert die Palette. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse. |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse. |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | Gibt die 32‑Bit‑ARGB‑Palettenfarbe nach Index zurück. |
| [get_color(index)](#get_color_index_8) | Gibt die Palettenfarbe nach Index zurück. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | Gibt den Index der nächstgelegenen Farbe zurück. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | Gibt den Index der nächstgelegenen Farbe zurück. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | Gibt den Index der nächstgelegenen Farbe zurück. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_entries | int[] | The 32‑Bit‑ARGB‑Farbenpaletteneinträge. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_entries | int[] | The 32‑Bit‑ARGB‑Farbenpaletteneinträge. |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Kopiert die Palette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Die neu erstellte und kopierte Palette oder null, wenn eine null‑Palette übergeben wurde. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Kopiert die Palette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette. |
| use_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Die neu erstellte und kopierte Palette oder null, wenn eine null‑Palette übergeben wurde. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_entries | int[] | The 32‑Bit‑ARGB‑Farbenpaletteneinträge. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_entries | int[] | The 32‑Bit‑ARGB‑Farbenpaletteneinträge. |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die Einträge der Farbpalette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die Einträge der Farbpalette. |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


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


### Method: get_color(index) {#get_color_index_8}


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


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

Gibt den Index der nächstgelegenen Farbe zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

Gibt den Index der nächstgelegenen Farbe zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

Gibt den Index der nächstgelegenen Farbe zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


