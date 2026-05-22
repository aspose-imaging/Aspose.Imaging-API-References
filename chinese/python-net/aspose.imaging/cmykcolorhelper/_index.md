---
title: "CmykColorHelper 类"
type: docs
weight: 1140
url: /zh/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。 |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。 |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。 |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | 从 32 位青色、品红、黄色和黑色值创建 CMYK。 |
| [get_c(cmyk)](#get_c_cmyk_10) | 获取青色分量值。 |
| [get_k(cmyk)](#get_k_cmyk_11) | 获取黑色分量值。 |
| [get_m(cmyk)](#get_m_cmyk_12) | 获取品红分量值。 |
| [get_y(cmyk)](#get_y_cmyk_13) | 获取黄色分量值。 |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | 将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | 将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | 将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | 将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | 使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | 使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | 将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | 使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | 使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | 使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | 使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | 使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | 使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | 将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | 将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | 将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | 将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | 将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | 将 ARGB 转换为 CMYK。 |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | 将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | 将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | 将 ARGB 转换为 CMYKA（带透明度）。 |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYKA（带 alpha）。 |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。 |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。 |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。 |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。 |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb | int | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb | int | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb | int | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转。 |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | int | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

从 32 位青色、品红、黄色和黑色值创建 CMYK。

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
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

获取青色分量值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk | int | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 青色分量值。 |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

获取黑色分量值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk | int | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 黑色分量值。 |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

获取品红分量值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk | int | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 品红色分量值。 |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

获取黄色分量值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk | int | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 黄色分量的值。 |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | ARGB 颜色以 32 位整数值的形式呈现。 |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int | CMYK 颜色以 32 位整数值呈现。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK 颜色以 32 位整数值呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK 像素以 32 位整数值的形式呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK 颜色以 32 位整数值呈现。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

使用默认配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK 像素以 32 位整数值的形式呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK 颜色以 32 位整数值呈现。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | ARGB 颜色以 32 位整数值的形式呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | ARGB 颜色以 32 位整数值的形式呈现。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

将 ARGB 转换为 CMYK。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | RGB 颜色以 32 位整数值的形式呈现。 |
| start_index | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | CMYK 颜色以字节数组的形式呈现。 |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb | int | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb | int | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | RGB 颜色以 32 位整数值的形式呈现。 |
| start_index | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |
| rgb_icc_stream | _io.BufferedRandom | RGB 配置文件流。 |
| cmyk_icc_stream | _io.BufferedRandom | CMYK 配置文件流。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | CMYK 颜色以字节数组的形式呈现。 |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 32 位整数值呈现。 |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

将 ARGB 转换为 CMYKA（带透明度）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | RGB 颜色以 32 位整数值的形式呈现。 |
| start_index | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | CMYK 颜色以字节数组的形式呈现。 |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义 ICC 配置文件将 RGB 转换为 CMYKA（带 alpha）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | RGB 颜色以 32 位整数值的形式呈现。 |
| start_index | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |
| rgb_icc_stream | _io.BufferedRandom | RGB 配置文件流。 |
| cmyk_icc_stream | _io.BufferedRandom | CMYK 配置文件流。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | CMYK 颜色以字节数组的形式呈现。 |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb | int | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转。 |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。<br/>            使用 PSD CMYK 格式 KCMY 字节顺序并反转通道值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 像素 | int[] | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值已反转.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 获取 CMYK 颜色空间中黑色的整数表示。
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# 黑色方块。
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# 在图像中心绘制黑色方块。
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

# 输出如下：
# 在不使用 ICC 配置文件的情况下将 RGB 转换为 CMYK。
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

