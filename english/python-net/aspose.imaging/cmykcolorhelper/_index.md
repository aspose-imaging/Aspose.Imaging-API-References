---
title: CmykColorHelper Class
type: docs
weight: 1090
url: /python-net/aspose.imaging/cmykcolorhelper/
---

Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

**Aspose.Imaging Version:** 23.6

The CmykColorHelper type exposes the following members:
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_0) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_1) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(pixel)](#to_cmyk_pixel_2) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(pixels)](#to_cmyk_pixels_3) | The conversion from ARGB colors to CMYK colors. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_4) | The conversion from CMYK colors to ARGB colors. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_5) | The conversion from CMYK colors to ARGB colors. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_6) |    |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_7) |    |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_8) |    |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_9) |    |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_10) |    |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_11) |    |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_12) |    |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_13) |    |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_14) |    |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_15) |    |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_16) |    |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_17) |    |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_18) |    |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_19) |    |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_20) |    |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_21) |    |
| [get_c(cmyk)](#get_c_cmyk_22) | Gets the cyan component value. |
| [get_m(cmyk)](#get_m_cmyk_23) | Gets the magenta component value. |
| [get_y(cmyk)](#get_y_cmyk_24) | Gets the yellow component value. |
| [get_k(cmyk)](#get_k_cmyk_25) | Gets the black component value. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_26) | Creates CMYK from a 32-bit cyan, magenta, yellow and black values. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_27) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_28) | Converts ARGB to CMYK. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_29) | Converts ARGB to CMYKA (with transparency). |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_30) | The conversion from ARGB color to CMYK color. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_31) | The conversion from ARGB colors to CMYK colors. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_32) | The conversion from CMYK colors to ARGB colors. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_33) | The conversion from CMYK colors to ARGB colors. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_34) | The conversion from CMYK colors to ARGB colors. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_35) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_36) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_37) | The conversion from CMYK color to ARGB Color using Icc conversion with default profiles. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_38) | The conversion from CMYK color to ARGB color using Icc conversion with custom profile. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_39) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_40) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_41) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_42) | Converts RGB to CMYK using custom ICC profiles. |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_43) | Converts RGB to CMYKA (with alpha) using custom ICC profiles. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_44) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_45) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_46) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_47) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_48) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_49) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_50) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_51) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_52) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |

### to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_0}


```
 to_cmyk(argb_pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The ARGB colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_1}


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


### to_cmyk(pixel)  [static] {#to_cmyk_pixel_2}


```
 to_cmyk(pixel) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### to_cmyk(pixels)  [static] {#to_cmyk_pixels_3}


```
 to_cmyk(pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_4}


```
 to_argb(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |


### to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_5}


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
| [Color](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |


### to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_6}


```
 to_argb_icc(cmyk_pixels) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) |  |


### to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_7}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int |  |
| cmyk_icc_stream | _io.BufferedRandom |  |
| rgb_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) |  |


### to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_8}


```
 to_argb_icc(cmyk_pixel) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) |  |


### to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_9}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom |  |
| rgb_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) |  |


### to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_10}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) |  |
| rgb_icc_stream | _io.BufferedRandom |  |
| cmyk_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_11}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int |  |
| rgb_icc_stream | _io.BufferedRandom |  |
| cmyk_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_12}


```
 to_cmyk_icc(pixels) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_13}


```
 to_cmyk_icc(pixels) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_14}


```
 to_cmyk_icc(pixel) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_15}


```
 to_cmyk_icc(argb) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_16}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color) |  |
| rgb_icc_stream | _io.BufferedRandom |  |
| cmyk_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_17}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int |  |
| rgb_icc_stream | _io.BufferedRandom |  |
| cmyk_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_18}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int |  |
| rgb_icc_stream | _io.BufferedRandom |  |
| cmyk_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_19}


```
 to_psd_cmyk_icc(pixels) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_20}


```
 to_psd_cmyk_icc(argb) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom |  |
| cmyk_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| int |  |


### get_c(cmyk)  [static] {#get_c_cmyk_22}


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


### get_m(cmyk)  [static] {#get_m_cmyk_23}


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


### get_y(cmyk)  [static] {#get_y_cmyk_24}


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


### get_k(cmyk)  [static] {#get_k_cmyk_25}


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


### from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_26}


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


### to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_27}


```
 to_cmyk_array(argb_pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The ARGB colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_28}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Converts ARGB to CMYK.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The CMYK colors presented as a byte array. |


### to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_29}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Converts ARGB to CMYKA (with transparency).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The CMYK colors presented as a byte array. |


### to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_30}


```
 to_cmyk_color(pixel) 
```

The conversion from ARGB color to CMYK color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color) | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_31}


```
 to_cmyk_colors(pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_32}


```
 to_argb_colors(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |


### to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_33}


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
| [Color](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |


### to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_34}


```
 to_argb32(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int | The ARGB colors presented as 32-bit integer values. |


### to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_35}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK pixels presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |


### to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_36}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK colors presented as 32-bit integer values. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |


### to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_37}


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
| [Color](/imaging/python-net/aspose.imaging/color) | The ARGB color. |


### to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_38}


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
| [Color](/imaging/python-net/aspose.imaging/color) | The ARGB color. |


### to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_39}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_40}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_41}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


### to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_42}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converts RGB to CMYK using custom ICC profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |
| rgb_icc_stream | _io.BufferedRandom | The RGB profile stream. |
| cmyk_icc_stream | _io.BufferedRandom | The CMYK profile stream. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The CMYK colors presented as a byte array. |


### to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converts RGB to CMYKA (with alpha) using custom ICC profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |
| rgb_icc_stream | _io.BufferedRandom | The RGB profile stream. |
| cmyk_icc_stream | _io.BufferedRandom | The CMYK profile stream. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The CMYK colors presented as a byte array. |


### to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_44}


```
 to_cmyk_array_with_def_icc(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_45}


```
 argb_32_to_cmyk_array(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_46}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.. |


### to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_47}


```
 to_cmyk_with_def_icc(pixel) 
```

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color) | The ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_48}


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


### argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_49}


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


### to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_50}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color) | The ARGB color. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK color presented as a 32-bit integer value. |


### argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_51}


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


### argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_52}


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


