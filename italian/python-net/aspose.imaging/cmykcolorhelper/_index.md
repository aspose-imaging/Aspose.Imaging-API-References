---
title: "Classe CmykColorHelper"
type: docs
weight: 1140
url: /it/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | Crea CMYK da valori a 32 bit di ciano, magenta, giallo e nero. |
| [get_c(cmyk)](#get_c_cmyk_10) | Restituisce il valore della componente ciano. |
| [get_k(cmyk)](#get_k_cmyk_11) | Restituisce il valore della componente nero. |
| [get_m(cmyk)](#get_m_cmyk_12) | Restituisce il valore della componente magenta. |
| [get_y(cmyk)](#get_y_cmyk_13) | Restituisce il valore della componente giallo. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | La conversione da colori CMYK a colori ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | La conversione da colori CMYK a colori ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | La conversione da colori CMYK a colori ARGB. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | La conversione da colori CMYK a colori ARGB. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | La conversione da colore CMYK a colore ARGB utilizzando la conversione Icc con profili predefiniti. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | La conversione da colore CMYK a colore ARGB utilizzando la conversione Icc con profilo personalizzato. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | La conversione da colori CMYK a colori ARGB. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili personalizzati. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili personalizzati. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili personalizzati. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | Converte ARGB in CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | La conversione da colore ARGB a colore CMYK. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Converte RGB in CMYK utilizzando profili ICC personalizzati. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | Converte ARGB in CMYKA (con trasparenza). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Converte RGB in CMYKA (con alfa) utilizzando profili ICC personalizzati. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | int | Il colore ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | int | Il colore ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | int | Il colore ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit in ordine di byte KCMY con valori dei canali invertiti. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori dei canali invertiti.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori dei canali invertiti.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int | Il colore ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori dei canali invertiti.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

Crea CMYK da valori a 32 bit di ciano, magenta, giallo e nero.

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
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Restituisce il valore della componente ciano.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente ciano. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Restituisce il valore della componente nero.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente nero. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Restituisce il valore della componente magenta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente magenta. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Restituisce il valore della componente giallo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente giallo. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori ARGB presentati come valori interi a 32 bit. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

La conversione da colore CMYK a colore ARGB utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il colore ARGB. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da colore CMYK a colore ARGB utilizzando la conversione Icc con profilo personalizzato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int | Il colore CMYK presentato come valore intero a 32 bit. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il colore ARGB. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int[] | I colori ARGB presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int[] | I colori ARGB presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Converte ARGB in CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int[] | I colori RGB presentati come valori interi a 32 bit. |
| start_index | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | I colori CMYK presentati come array di byte. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

La conversione da colore ARGB a colore CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | int | Il colore ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | int | Il colore ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | I colori ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converte RGB in CMYK utilizzando profili ICC personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori RGB presentati come valori interi a 32 bit. |
| start_index | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso del profilo RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso del profilo CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | I colori CMYK presentati come array di byte. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Converte ARGB in CMYKA (con trasparenza).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int[] | I colori RGB presentati come valori interi a 32 bit. |
| start_index | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | I colori CMYK presentati come array di byte. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converte RGB in CMYKA (con alfa) utilizzando profili ICC personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori RGB presentati come valori interi a 32 bit. |
| start_index | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso del profilo RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso del profilo CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | I colori CMYK presentati come array di byte. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | int | Il colore ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il colore CMYK presentato come valore intero a 32 bit in ordine di byte KCMY con valori dei canali invertiti. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori dei canali invertiti.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori dei canali invertiti.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.<br/>            Utilizza il formato PSD CMYK ordine byte KCMY con valori di canale invertiti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | int[] | I colori ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori dei canali invertiti.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Ottieni una rappresentazione intera del nero nello spazio colore CMYK.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# Il quadrato nero.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Disegna il quadrato nero al centro dell'immagine.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_cmyk_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveCmyk32Pixels.png"))


```

### The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles. {#example_178}
``` python

from aspose.imaging import Color, CmykColorHelper

rgbColors = [Color.red, Color.green, Color.blue]

print("Convert RGB to CMYK without using ICC profiles.")
for rgbColor in rgbColors:
	cmyk = CmykColorHelper.to_cmyk(rgbColor)
	c = CmykColorHelper.get_c(cmyk)
	m = CmykColorHelper.get_m(cmyk)
	y = CmykColorHelper.get_y(cmyk)
	k = CmykColorHelper.get_k(cmyk)
	print(f"RGB({rgbColor.r},{rgbColor.g},{rgbColor.b})\t\t=> CMYK({c},{m},{y},{k})")

# L'output appare così:
# Converti RGB in CMYK senza utilizzare profili ICC.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

