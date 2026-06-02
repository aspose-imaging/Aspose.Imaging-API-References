---
title: "Classe ColorPalette"
type: docs
weight: 1190
url: /it/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Restituisce un array di strutture ARGB a 32 bit. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Restituisce un array di strutture [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Restituisce il conteggio delle voci. |
| is_compact_palette | bool | r | Restituisce o imposta un valore che indica se viene utilizzata una palette compatta. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copia la palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copia la palette. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | Restituisce il colore della palette ARGB a 32 bit per indice. |
| [get_color(index)](#get_color_index_8) | Restituisce il colore della palette per indice. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | Restituisce l'indice del colore più vicino. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | Restituisce l'indice del colore più vicino. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | Restituisce l'indice del colore più vicino. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_entries | int[] | Le voci della tavolozza dei colori ARGB a 32 bit. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_entries | int[] | Le voci della tavolozza dei colori ARGB a 32 bit. |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copia la palette.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza dei colori. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | La tavolozza appena creata e copiata o null se è stata passata una tavolozza null. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copia la palette.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza dei colori. |
| use_compact_palette | bool | Indica se la tavolozza è compatta. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | La tavolozza appena creata e copiata o null se è stata passata una tavolozza null. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_entries | int[] | Le voci della tavolozza dei colori ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_entries | int[] | Le voci della tavolozza dei colori ARGB a 32 bit. |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Le voci della tavolozza dei colori. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Le voci della tavolozza dei colori. |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


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


### Method: get_color(index) {#get_color_index_8}


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


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

Restituisce l'indice del colore più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_color | int | Il colore ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice del colore più vicino. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

Restituisce l'indice del colore più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_color | int | Il colore ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice del colore più vicino. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

Restituisce l'indice del colore più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice del colore più vicino. |


