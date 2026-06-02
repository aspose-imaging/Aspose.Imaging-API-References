---
title: "Clase CmykColorHelper"
type: docs
weight: 1140
url: /es/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits. |
| [get_c(cmyk)](#get_c_cmyk_10) | Obtiene el valor del componente cian. |
| [get_k(cmyk)](#get_k_cmyk_11) | Obtiene el valor del componente negro. |
| [get_m(cmyk)](#get_m_cmyk_12) | Obtiene el valor del componente magenta. |
| [get_y(cmyk)](#get_y_cmyk_13) | Obtiene el valor del componente amarillo. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | La conversión de colores CMYK a colores ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | La conversión de colores CMYK a colores ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | La conversión de colores CMYK a colores ARGB. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | La conversión de colores CMYK a colores ARGB. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | La conversión de color CMYK a color ARGB usando conversión Icc con perfiles predeterminados. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | La conversión de color CMYK a color ARGB usando conversión Icc con perfil personalizado. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | La conversión de colores CMYK a colores ARGB. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | Convierte ARGB a CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | La conversión de color ARGB a color CMYK. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Convierte RGB a CMYK usando perfiles ICC personalizados. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | Convierte ARGB a CMYKA (con transparencia). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Convierte RGB a CMYKA (con alfa) usando perfiles ICC personalizados. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | int | El color ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | int | El color ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | int | El color ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits en orden de bytes KCMY con valores de canal invertidos. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | int | El color ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cian | int | El componente cian. Los valores válidos son de 0 a 255. |
| magenta | int | El componente magenta. Los valores válidos son de 0 a 255. |
| amarillo | int | El componente amarillo. Los valores válidos son de 0 a 255. |
| negro | int | El componente negro. Los valores válidos son de 0 a 255. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Obtiene el valor del componente cian.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente cian. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Obtiene el valor del componente negro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente negro. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Obtiene el valor del componente magenta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente magenta. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Obtiene el valor del componente amarillo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente amarillo. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores ARGB presentados como valores enteros de 32 bits. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

La conversión de color CMYK a color ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El color ARGB. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de color CMYK a color ARGB usando conversión Icc con perfil personalizado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int | El color CMYK presentado como un valor entero de 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El color ARGB. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int[] | Los colores ARGB presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int[] | Los colores ARGB presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Convierte ARGB a CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| start_index | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los colores CMYK presentados como una matriz de bytes. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

La conversión de color ARGB a color CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | El color ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | int | El color ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | int | El color ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Los colores ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Convierte RGB a CMYK usando perfiles ICC personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| start_index | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |
| rgb_icc_stream | _io.BufferedRandom | El flujo del perfil RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo del perfil CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los colores CMYK presentados como una matriz de bytes. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | El color ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | El color ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Convierte ARGB a CMYKA (con transparencia).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| start_index | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los colores CMYK presentados como una matriz de bytes. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Convierte RGB a CMYKA (con alfa) usando perfiles ICC personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| start_index | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |
| rgb_icc_stream | _io.BufferedRandom | El flujo del perfil RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo del perfil CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los colores CMYK presentados como una matriz de bytes. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | int | El color ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits en orden de bytes KCMY con valores de canal invertidos. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.<br/>            Utiliza el formato PSD CMYK orden de bytes KCMY con valores de canal invertidos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| píxeles | int[] | Los colores ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Obtener una representación entera del negro en el espacio de color CMYK.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# El cuadrado negro.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Dibujar el cuadrado negro en el centro de la imagen.
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

# La salida se ve así:
# Convertir RGB a CMYK sin usar perfiles ICC.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

