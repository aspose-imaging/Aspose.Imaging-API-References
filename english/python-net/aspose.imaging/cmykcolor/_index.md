---
title: CmykColor Class
type: docs
weight: 1080
url: /python-net/aspose.imaging/cmykcolor/
---

The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

**Aspose.Imaging Version:** 23.6

The CmykColor type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [CmykColor()](#CmykColor__0) | Initializes a new instance of the CmykColor class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) | r | Gets the empty. |
| c | byte | r | Gets the cyan component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
| m | byte | r | Gets the magenta component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
| y | byte | r | Gets the yellow component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
| k | byte | r | Gets the black component value of this [Color](/imaging/python-net/aspose.imaging/color/) structure. |
| is_empty | bool | r | Gets a value indicating whether this [Color](/imaging/python-net/aspose.imaging/color/) structure is uninitialized. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_1) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_2) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />. |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_3) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb(int[])" />. |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_4) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb(int[])" />. |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_5) |    |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_6) |    |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_7) |    |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) |    |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_9) | Creates a [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) structure from a 32-bit cyan, magenta, yellow and black values.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.FromComponents(int,int,int,int)" />. |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_10) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />. |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_11) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb(int[])" />. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_12) | The conversion from CMYKColor to 32-bit ARGB Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb32(int[])" />. |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_13) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />. |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_14) | The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgbIcc(int[])" />. |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_15) |    |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_16) | The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgbIcc(int[],System.IO.Stream,System.IO.Stream)" />. |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) |    |
| [to_value()](#to_value__18) | The to value. |

### CmykColor() {#CmykColor__0}


```
 CmykColor() 
```

Initializes a new instance of the CmykColor class

### to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_1}


```
 to_cmyk(argb_pixels) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The pixels of 32-bit ARGB format. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The <see cref="T:Aspose:Imaging:CmykColor[]" />. |


### to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_2}


```
 to_cmyk(argb_pixel) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) | The <see cref="T:Aspose:Imaging:CmykColor[]" />. |


### to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_3}


```
 to_color(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The array of the ARGB colors. |


### to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_4}


```
 to_color(cmyk_pixel) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) | The array of the ARGB colors. |


### to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_5}


```
 to_color_icc(cmyk_pixels) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) |  |


### to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_6}


```
 to_color_icc(cmyk_pixel) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) |  |


### to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_7}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom |  |
| rgb_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) |  |


### to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom |  |
| rgb_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) |  |


### from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_9}


```
 from_params(cyan, magenta, yellow, black) 
```

Creates a [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) structure from a 32-bit cyan, magenta, yellow and black values.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.FromComponents(int,int,int,int)" />.

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
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) | The [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_10}


```
 to_cmyk_colors(argb_pixels) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The pixels of 32-bit ARGB format. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The <see cref="T:Aspose:Imaging:CmykColor[]" />. |


### to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_11}


```
 to_colors(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The array of the ARGB colors. |


### to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_12}


```
 to_argb32(cmyk_pixels) 
```

The conversion from CMYKColor to 32-bit ARGB Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgb32(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| int | The array of the 32-bit ARGB color. |


### to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_13}


```
 to_cmyk_color(argb_pixel) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToCmyk(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) | The <see cref="T:Aspose:Imaging:CmykColor[]" />. |


### to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_14}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgbIcc(int[])" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The <see cref="T:Aspose.Imaging.Color[]" />. |


### to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_15}


```
 to_color_with_def_icc(cmyk_pixels) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) |  |


### to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_16}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective <see cref="M:Aspose.Imaging.CmykColorHelper.ToArgbIcc(int[],System.IO.Stream,System.IO.Stream)" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing icc cmyk profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing icc rgb profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The <see cref="T:Aspose.Imaging.Color[]" />. |


### to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom |  |
| rgb_icc_stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) |  |


### to_value() {#to_value__18}


```
 to_value() 
```

The to value.

**Returns**

| Type | Description |
| :- | :- |
| long | The int. |


