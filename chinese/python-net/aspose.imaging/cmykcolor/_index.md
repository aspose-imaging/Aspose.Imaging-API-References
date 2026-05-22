---
title: "CmykColor 类"
type: docs
weight: 1130
url: /zh/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | 初始化 CmykColor 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| c | System.Byte | r | 获取此 [Color](/imaging/python-net/aspose.imaging/color/) 结构的青色分量值。 |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | 获取空值。 |
| is_empty | bool | r | 获取一个值，指示此 [Color](/imaging/python-net/aspose.imaging/color/) 结构是否未初始化。 |
| k | System.Byte | r | 获取此 [Color](/imaging/python-net/aspose.imaging/color/) 结构的黑色分量值。 |
| m | System.Byte | r | 获取此 [Color](/imaging/python-net/aspose.imaging/color/) 结构的品红分量值。 |
| y | System.Byte | r | 获取此 [Color](/imaging/python-net/aspose.imaging/color/) 结构的黄色分量值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | 从 32 位青色、品红、黄色和黑色值创建一个 [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) 结构。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。 |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 32 位 ARGB 颜色。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。 |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | 将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。 |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | 将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。 |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | 从 32 位 ARGB 到 CMYKColor 的转换。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | 将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。 |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | 使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | 使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | 使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | 使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | 使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | 使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | 使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | 使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | 使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | 使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | 使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | 该 to 值。 |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

初始化 CmykColor 类的新实例

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

从 32 位青色、品红、黄色和黑色值创建一个 [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) 结构。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 青色 | int | 青色分量。有效值范围为 0 到 255。 |
| 品红色 | int | 品红色分量。有效值范围为 0 到 255。 |
| 黄色 | int | 黄色分量。有效值范围为 0 到 255。 |
| 黑色 | int | 黑色分量。有效值范围为 0 到 255。 |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | 此 [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/)。 |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

使用默认配置文件的 ICC 转换将 CMYKColor 转换为 32 位 ARGB 颜色。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 该 32 位 ARGB 颜色的数组。 |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | 此 [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/)。 |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | 该 32 位 ARGB 格式的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 此 [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/)。 |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

从 32 位 ARGB 到 CMYKColor 的转换。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixel | int | 该 32 位 ARGB 格式的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | 此 [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/)。 |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | 该 32 位 ARGB 格式的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 此 [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/)。 |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该 ARGB 颜色的数组。 |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 该 ARGB 颜色的数组。 |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该 [Color[]](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | 包含 ICC CMYK 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 ICC RGB 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该 [Color[]](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 该 [Color[]](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 ICC CMYK 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 ICC RGB 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 该 [Color[]](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该 [Color](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 ICC CMYK 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 ICC RGB 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该 [Color](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 该 ARGB 颜色的数组。 |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

使用 ICC 转换和默认配置文件将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 该 [Color[]](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 该 CMYK 格式中 CMYKColor 类型的像素。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 ICC CMYK 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 ICC RGB 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 该 [Color[]](/imaging/python-net/aspose.imaging/color/)。 |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

该 to 值。

**Returns**

| Type | Description |
| :- | :- |
| int | 该 长 CMYK 值。 |


