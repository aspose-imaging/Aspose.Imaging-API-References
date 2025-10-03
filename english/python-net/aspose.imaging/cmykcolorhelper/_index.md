---
title: CmykColorHelper Class
type: docs
weight: 1140
url: /python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | Creates CMYK from a 32-bit cyan, magenta, yellow and black values. |
| [get_c(cmyk)](#get_c_cmyk_10) | Gets the cyan component value. |
| [get_k(cmyk)](#get_k_cmyk_11) | Gets the black component value. |
| [get_m(cmyk)](#get_m_cmyk_12) | Gets the magenta component value. |
| [get_y(cmyk)](#get_y_cmyk_13) | Gets the yellow component value. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | The conversion from CMYK colors to ARGB colors. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | The conversion from CMYK colors to ARGB colors. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | The conversion from CMYK colors to ARGB colors. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | The conversion from CMYK colors to ARGB colors. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | The conversion from CMYK color to ARGB Color using Icc conversion with default profiles. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | The conversion from CMYK color to ARGB color using Icc conversion with custom profile. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | The conversion from CMYK colors to ARGB colors. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | Converts ARGB to CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | The conversion from ARGB color to CMYK color. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Converts RGB to CMYK using custom ICC profiles. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | Converts ARGB to CMYKA (with transparency). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Converts RGB to CMYKA (with alpha) using custom ICC profiles. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int | The ARGB color. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value in KCMY byte order with inverted channel values. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | int | The ARGB color. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

Creates CMYK from a 32-bit cyan, magenta, yellow and black values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cyan | int | The cyan component. Valid values are 0 through 255. |
| magenta | int | The magenta component. Valid values are 0 through 255. |
| yellow | int | The yellow component. Valid values are 0 through 255. |
| black | int | The black component. Valid values are 0 through 255. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Gets the cyan component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The cyan component value. |



**See also:**

**[Example # 1](#example_163)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Gets the black component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The black component value. |



**See also:**

**[Example # 1](#example_163)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Gets the magenta component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The magenta component value. |



**See also:**

**[Example # 1](#example_163)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Gets the yellow component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The yellow component value. |



**See also:**

**[Example # 1](#example_163)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The ARGB colors presented as 32-bit integer values. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

The conversion from CMYK color to ARGB Color using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB color. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYK color to ARGB color using Icc conversion with custom profile.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int | The CMYK color presented as a 32-bit integer value. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB color. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | The CMYK pixels presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | The CMYK colors presented as 32-bit integer values. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | The CMYK pixels presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | The CMYK colors presented as 32-bit integer values. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | The ARGB colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |



**See also:**

**[Example # 1](#example_163)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | The ARGB colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Converts ARGB to CMYK.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The CMYK colors presented as a byte array. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

The conversion from ARGB color to CMYK color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int | The ARGB color. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converts RGB to CMYK using custom ICC profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |
| rgb_icc_stream | _io.BufferedRandom | The RGB profile stream. |
| cmyk_icc_stream | _io.BufferedRandom | The CMYK profile stream. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The CMYK colors presented as a byte array. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | The ARGB color. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Converts ARGB to CMYKA (with transparency).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The CMYK colors presented as a byte array. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converts RGB to CMYKA (with alpha) using custom ICC profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |
| rgb_icc_stream | _io.BufferedRandom | The RGB profile stream. |
| cmyk_icc_stream | _io.BufferedRandom | The CMYK profile stream. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The CMYK colors presented as a byte array. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value in KCMY byte order with inverted channel values. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int[] | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Get an integer representation of black in the CMYK color space.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# The black square.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Draw the black square at the center of the image.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_cmyk_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveCmyk32Pixels.png"))


```

### The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles. {#example_163}
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

# The output looks like this:
# Convert RGB to CMYK without using ICC profiles.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

