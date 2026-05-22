---
title: "PixelDataFormat 类"
type: docs
weight: 6920
url: /zh/python-net/aspose.imaging/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 定义为每像素 16 位，其中最多 16 位表示灰度强度。 |
| bits_per_pixel | int | r | 获取每像素的位数。 |
| 标题 | string | r | 获取像素数据格式的标题。 |
| channel_bits | int[] | r | 获取每个通道的位计数。 |
| channels_count | int | r | 获取通道计数。 |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取定义为每像素 32 位、每个青色、品红、黄色和黑色各 8 位的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取 acmyk。 |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r/w | 获取定义为每像素 8 位、8 位表示 0-255 区间灰度强度的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取定义为每像素 16 位、8 位表示 0-255 区间灰度强度且额外包含 8 位 alpha 分量的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | r | 获取像素格式。 |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取定义为每像素 16 位、红、绿、蓝各 5 位且未定义 alpha 的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取定义为每像素 16 位、红 5 位、绿 6 位、蓝 5 位且未定义 alpha 的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每像素 24 位且每个 alpha、红、绿、蓝各 8 位定义的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)，但未定义 alpha。 |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每像素 24 位且每个 alpha、红、绿、蓝各 8 位定义的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)，但未定义 alpha。 |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每像素 32 位且每个 alpha、红、绿、蓝各 8 位定义的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每种颜色 1 位索引的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。<br/>            索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。<br/>            使用时需谨慎，因为可能需要从一种调色板转换到另一种，或从 RGBA 转换为索引颜色模型。 |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每种颜色 2 位索引的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。<br/>            索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。<br/>            使用时需谨慎，因为可能需要从一种调色板转换到另一种，或从 RGBA 转换为索引颜色模型。 |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每种颜色 4 位索引的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。<br/>            索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。<br/>            使用时需谨慎，因为可能需要从一种调色板转换到另一种，或从 RGBA 转换为索引颜色模型。 |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每种颜色 8 位索引的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。<br/>            索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。<br/>            使用时需谨慎，因为可能需要从一种调色板转换到另一种，或从 RGBA 转换为索引颜色模型。 |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每像素 32 位且每个 alpha、红、绿、蓝各 8 位定义的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每像素 24 位且每个亮度、蓝差、红差色度分量各 8 位定义的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取为每像素 32 位且每个亮度、蓝差、红差和黑色色度分量各 8 位定义的 [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/)。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | 获取具有指定每样本位数的 BGRA 颜色。 |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | 获取具有指定每样本位数的 BGRA 颜色。 |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | 获取具有指定每样本位数的 CIE Lab 颜色。 |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | 获取具有指定每样本位数的 CMYK 颜色。 |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | 获取具有指定每样本位数的 CMYK 颜色。 |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | 获取具有指定每样本位数的 CMYKA 颜色。 |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | 获取具有指定每样本位数的灰度颜色。 |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | 获取具有指定每样本位数的 GrayscaleAlpha 颜色。 |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | 获取具有指定每样本位数的 GrayscaleAlpha 颜色。 |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | 获取具有指定每样本位数的 RGB 颜色。 |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | 获取具有指定每样本位数的 RGB 颜色。 |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | 获取具有指定每样本位数的 BGRA 索引颜色。 |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | 获取具有指定每样本位数的 RGBA 颜色。 |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | 获取具有指定每样本位数的 RGBA 颜色。 |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | 获取具有指定每样本位数的 YCCK 颜色。 |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

获取具有指定每样本位数的 BGRA 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA 颜色。 |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

获取具有指定每样本位数的 BGRA 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA 颜色。 |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

获取具有指定每样本位数的 CIE Lab 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_l | int | 每个 L 通道的位数。 |
| bits_per_a | int | 每个 A 通道的位数。 |
| bits_per_b | int | 每个 B 通道的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CIE Lab 颜色。 |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

获取具有指定每样本位数的 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_cyan_channel | int | 每个 Cyan 通道的位数。 |
| bits_per_magenta_channel | int | 每个 Magenta 通道的位数。 |
| bits_per_yellow_channel | int | 每个 Yellow 通道的位数。 |
| bits_per_key_channel | int | 每个 Key 通道的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK 颜色。 |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

获取具有指定每样本位数的 CMYK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK 颜色。 |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

获取具有指定每样本位数的 CMYKA 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_cyan_channel | int | 每个 Cyan 通道的位数。 |
| bits_per_magenta_channel | int | 每个 Magenta 通道的位数。 |
| bits_per_yellow_channel | int | 每个 Yellow 通道的位数。 |
| bits_per_key_channel | int | 每个 Key 通道的位数。 |
| bits_per_alpha_channel | int | 每个 Alpha 通道的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK 颜色。 |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

获取具有指定每样本位数的灰度颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | 灰度颜色。 |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

获取具有指定每样本位数的 GrayscaleAlpha 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | 灰度Alpha颜色。 |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

获取具有指定每样本位数的 GrayscaleAlpha 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |
| alpha_channel_bits | int | alpha 通道中每个样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | 灰度Alpha颜色。 |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

获取具有指定每样本位数的 RGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_red_channel | int | 每个 Red 通道的位数。 |
| bits_per_green_channel | int | 每个 Green 通道的位数。 |
| bits_per_blue_channel | int | 每个 Blue 通道的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGB 颜色。 |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

获取具有指定每样本位数的 RGB 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGB 颜色。 |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

获取具有指定每样本位数的 BGRA 索引颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA 颜色。 |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

获取具有指定每样本位数的 RGBA 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_red_channel | int | 每个 Red 通道的位数。 |
| bits_per_green_channel | int | 每个 Green 通道的位数。 |
| bits_per_blue_channel | int | 每个 Blue 通道的位数。 |
| bits_per_alpha_channel | int | 每个 Alpha 通道的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA 颜色。 |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

获取具有指定每样本位数的 RGBA 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA 颜色。 |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

获取具有指定每样本位数的 YCbCr 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr 颜色。 |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

获取具有指定每样本位数的 YCbCr 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_y | int | 每个 Y 通道的位数。 |
| bits_per_cb | int | 每个 Cb 通道的位数。 |
| bits_per_cr | int | 每个 Cr 通道的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr 颜色。 |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

获取具有指定每样本位数的 YCCK 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | 每样本的位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCCK 颜色。 |


