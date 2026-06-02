---
title: "CmykColorHelper-klass"
type: docs
weight: 1140
url: /sv/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden. |
| [get_c(cmyk)](#get_c_cmyk_10) | Hämtar cyan-komponentens värde. |
| [get_k(cmyk)](#get_k_cmyk_11) | Hämtar svart-komponentens värde. |
| [get_m(cmyk)](#get_m_cmyk_12) | Hämtar magenta-komponentens värde. |
| [get_y(cmyk)](#get_y_cmyk_13) | Hämtar gul-komponentens värde. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och standardprofiler. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och anpassad profil. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | Konverterar ARGB till CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | Konverteringen från ARGB-färg till CMYK-färg. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Konverterar RGB till CMYK med anpassade ICC-profiler. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | Konverterar ARGB till CMYKA (med transparens). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Konverterar RGB till CMYKA (med alfa) med hjälp av anpassade ICC-profiler. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb | int | ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb | int | ARGB-färgen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb | int | ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde i KCMY-byteordning med inverterade kanalvärden. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | int | ARGB-färgen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cyan | int | Cyan-komponenten. Giltiga värden är 0 till 255. |
| magenta | int | Magenta-komponenten. Giltiga värden är 0 till 255. |
| yellow | int | Gul-komponenten. Giltiga värden är 0 till 255. |
| black | int | Svart-komponenten. Giltiga värden är 0 till 255. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Hämtar cyan-komponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Cyan-komponentvärdet. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Hämtar svart-komponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Svart-komponentvärdet. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Hämtar magenta-komponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Magenta-komponentvärdet. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Hämtar gul-komponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det gula komponentvärdet. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | ARGB-färgerna som presenteras som 32-bitars heltalsvärden. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgen. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och anpassad profil.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgen. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK-pixlarna som presenteras som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK-pixlarna som presenteras som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int[] | ARGB-färgerna som presenteras som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int[] | ARGB-färgerna som presenteras som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Konverterar ARGB till CMYK.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int[] | RGB-färgerna som presenteras som 32-bitars heltalsvärden. |
| start_index | int | Startindex för RGB-färgen. |
| length | int | Antalet RGB-pixlar att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | CMYK-färgerna som presenteras som en bytearray. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

Konverteringen från ARGB-färg till CMYK-färg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb | int | ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb | int | ARGB-färgen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB-färgerna. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Konverterar RGB till CMYK med anpassade ICC-profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | RGB-färgerna som presenteras som 32-bitars heltalsvärden. |
| start_index | int | Startindex för RGB-färgen. |
| length | int | Antalet RGB-pixlar att konvertera. |
| rgb_icc_stream | _io.BufferedRandom | RGB-profilströmmen. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK-profilströmmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | CMYK-färgerna som presenteras som en bytearray. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB-färgen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Konverterar ARGB till CMYKA (med transparens).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int[] | RGB-färgerna som presenteras som 32-bitars heltalsvärden. |
| start_index | int | Startindex för RGB-färgen. |
| length | int | Antalet RGB-pixlar att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | CMYK-färgerna som presenteras som en bytearray. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Konverterar RGB till CMYKA (med alfa) med hjälp av anpassade ICC-profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | RGB-färgerna som presenteras som 32-bitars heltalsvärden. |
| start_index | int | Startindex för RGB-färgen. |
| length | int | Antalet RGB-pixlar att konvertera. |
| rgb_icc_stream | _io.BufferedRandom | RGB-profilströmmen. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK-profilströmmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | CMYK-färgerna som presenteras som en bytearray. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb | int | ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde i KCMY-byteordning med inverterade kanalvärden. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.<br/>            Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int[] | ARGB-färgerna. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Hämta en heltalsrepresentation av svart i CMYK-färgrymden.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# Den svarta kvadraten.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Rita den svarta kvadraten i bildens centrum.
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

# Utdata ser ut så här:
# Konvertera RGB till CMYK utan att använda ICC-profiler.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

