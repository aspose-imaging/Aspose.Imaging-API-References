---
title: "Classe CmykColorHelper"
type: docs
weight: 1140
url: /fr/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | Crée du CMYK à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. |
| [get_c(cmyk)](#get_c_cmyk_10) | Obtient la valeur du composant cyan. |
| [get_k(cmyk)](#get_k_cmyk_11) | Obtient la valeur du composant noir. |
| [get_m(cmyk)](#get_m_cmyk_12) | Obtient la valeur du composant magenta. |
| [get_y(cmyk)](#get_y_cmyk_13) | Obtient la valeur du composant jaune. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | La conversion de couleurs CMYK en couleurs ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | La conversion de couleurs CMYK en couleurs ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | La conversion de couleurs CMYK en couleurs ARGB. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | La conversion de couleurs CMYK en couleurs ARGB. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | La conversion d'une couleur CMYK en Couleur ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion Icc avec un profil personnalisé. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | La conversion de couleurs CMYK en couleurs ARGB. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | La conversion de couleurs ARGB en couleurs CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | La conversion de couleurs ARGB en couleurs CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | La conversion de couleurs ARGB en couleurs CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | La conversion de couleurs ARGB en couleurs CMYK. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | La conversion de couleurs ARGB en couleurs CMYK. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | Convertit ARGB en CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | La conversion d'une couleur ARGB en couleur CMYK. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | La conversion de couleurs ARGB en couleurs CMYK. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Convertit RGB en CMYK en utilisant des profils ICC personnalisés. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | Convertit ARGB en CMYKA (avec transparence). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Convertit le RGB en CMYKA (avec alpha) en utilisant des profils ICC personnalisés. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb | int | La couleur ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb | int | La couleur ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb | int | La couleur ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | int | La couleur ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

Crée du CMYK à partir de valeurs cyan, magenta, jaune et noir sur 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cyan | int | Le composant cyan. Les valeurs valides sont de 0 à 255. |
| magenta | int | Le composant magenta. Les valeurs valides sont de 0 à 255. |
| yellow | int | Le composant jaune. Les valeurs valides sont de 0 à 255. |
| black | int | Le composant noir. Les valeurs valides sont de 0 à 255. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Obtient la valeur du composant cyan.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant cyan. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Obtient la valeur du composant noir.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant noir. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Obtient la valeur du composant magenta.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant magenta. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Obtient la valeur du composant jaune.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant jaune. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

La conversion de couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

La conversion de couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

La conversion de couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs ARGB présentées sous forme de valeurs entières 32 bits. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

La conversion de couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

La conversion d'une couleur CMYK en Couleur ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | La couleur ARGB. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion Icc avec un profil personnalisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | La couleur ARGB. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

La conversion de couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

La conversion de couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | Les couleurs ARGB présentées sous forme de valeurs entières 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

La conversion de couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | Les couleurs ARGB présentées sous forme de valeurs entières 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Convertit ARGB en CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| start_index | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les couleurs CMYK présentées sous forme d'un tableau d'octets. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

La conversion d'une couleur ARGB en couleur CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb | int | La couleur ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb | int | La couleur ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les couleurs ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Convertit RGB en CMYK en utilisant des profils ICC personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| start_index | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |
| rgb_icc_stream | _io.BufferedRandom | Le flux du profil RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux du profil CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les couleurs CMYK présentées sous forme d'un tableau d'octets. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Convertit ARGB en CMYKA (avec transparence).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| start_index | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les couleurs CMYK présentées sous forme d'un tableau d'octets. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Convertit le RGB en CMYKA (avec alpha) en utilisant des profils ICC personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| start_index | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |
| rgb_icc_stream | _io.BufferedRandom | Le flux du profil RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux du profil CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les couleurs CMYK présentées sous forme d'un tableau d'octets. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb | int | La couleur ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée sous forme de valeur entière 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion de couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.<br/>            Utilise le format PSD CMYK ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int[] | Les couleurs ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil ICC CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Obtenez une représentation entière du noir dans l'espace colorimétrique CMYK.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# Le carré noir.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Dessinez le carré noir au centre de l'image.
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

# La sortie ressemble à ceci :
# Convertissez RGB en CMYK sans utiliser de profils ICC.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

