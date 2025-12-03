---
title: CmykColor Class
type: docs
weight: 1130
url: /python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initializes a new instance of the CmykColor class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | System.Byte | r | Gets the cyan component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Gets the empty. |
| is_empty | bool | r | Gets a value indicating whether this [Color](/imaging/python-net/aspose.imaging/color/) structure is uninitialized. |
| k | System.Byte | r | Gets the black component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
| m | System.Byte | r | Gets the magenta component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
| y | System.Byte | r | Gets the yellow component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Creates a [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) structure from a 32-bit cyan, magenta, yellow and black values.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | The conversion from CMYKColor to 32-bit ARGB Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | The conversion from 32-bit ARGB to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | The to value. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initializes a new instance of the CmykColor class

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Creates a [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) structure from a 32-bit cyan, magenta, yellow and black values.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

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
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | The [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

The conversion from CMYKColor to 32-bit ARGB Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The array of the 32-bit ARGB color. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | The [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | The pixels of 32-bit ARGB format. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

The conversion from 32-bit ARGB to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixel | int | The pixel of 32-bit ARGB format. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | The [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | The pixels of 32-bit ARGB format. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The array of the ARGB colors. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The array of the ARGB colors. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing icc cmyk profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing icc rgb profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixels of CMYKColor type in CMYK format. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing icc cmyk profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing icc rgb profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixel of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixel of CMYKColor type in CMYK format. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing icc cmyk profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing icc rgb profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The array of the ARGB colors. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The pixels of CMYKColor type in CMYK format. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing icc cmyk profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing icc rgb profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

The to value.

**Returns**

| Type | Description |
| :- | :- |
| int | The long CMYK value. |


