---
title: "Classe CmykColor"
type: docs
weight: 1130
url: /it/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Inizializza una nuova istanza della classe CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| c | System.Byte | r | Ottiene il valore della componente ciano di questa struttura [Color](/imaging/python-net/aspose.imaging/color/). |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Ottiene il valore vuoto. |
| is_empty | bool | r | Ottiene un valore che indica se questa struttura [Color](/imaging/python-net/aspose.imaging/color/) è non inizializzata. |
| k | System.Byte | r | Ottiene il valore della componente nera di questa struttura [Color](/imaging/python-net/aspose.imaging/color/). |
| m | System.Byte | r | Ottiene il valore della componente magenta di questa struttura [Color](/imaging/python-net/aspose.imaging/color/). |
| y | System.Byte | r | Ottiene il valore della componente gialla di questa struttura [Color](/imaging/python-net/aspose.imaging/color/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Crea una struttura [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) da valori a 32 bit di ciano, magenta, giallo e nero.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | La conversione da CMYKColor a colore ARGB a 32 bit utilizzando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | La conversione da 32-bit ARGB a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | Il valore to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Inizializza una nuova istanza della classe CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Crea una struttura [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) da valori a 32 bit di ciano, magenta, giallo e nero.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ciano | int | Il componente ciano. I valori validi sono da 0 a 255. |
| magenta | int | Il componente magenta. I valori validi sono da 0 a 255. |
| giallo | int | Il componente giallo. I valori validi sono da 0 a 255. |
| nero | int | Il componente nero. I valori validi sono da 0 a 255. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Il [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

La conversione da CMYKColor a colore ARGB a 32 bit utilizzando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | I pixel di tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array del colore 32-bit ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Il [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int[] | I pixel del formato 32-bit ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Il [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

La conversione da 32-bit ARGB a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixel | int | Il pixel del formato 32-bit ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Il [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int[] | I pixel del formato 32-bit ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Il [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | L'array dei colori ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | I pixel di tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array dei colori ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc rgb. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | I pixel di tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Il [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | I pixel di tipo CMYKColor in formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc rgb. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Il [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Il pixel di tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Il pixel di tipo CMYKColor in formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc rgb. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | I pixel di tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array dei colori ARGB. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | I pixel di tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Il [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare una versione più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | I pixel di tipo CMYKColor in formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc rgb. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Il [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

Il valore to.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore CMYK lungo. |


