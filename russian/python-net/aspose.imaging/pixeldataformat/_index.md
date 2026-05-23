---
title: "Класс PixelDataFormat"
type: docs
weight: 6920
url: /ru/python-net/aspose.imaging/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Определено для 16 бит на пиксель с до 16 битами, представляющими интенсивность в градациях серого. |
| bits_per_pixel | int | r | Получает количество бит на пиксель. |
| заголовок | string | r | Получает подпись формата данных пикселя. |
| channel_bits | int[] | r | Получает количество бит для каждого канала. |
| channels_count | int | r | Получает количество каналов. |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определённый для 32 бит на пиксель с 8 битами для каждого из циана, мадженты, желтого и черного. |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает acmyk. |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r/w | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определённый для 8 бит на пиксель с 8 битами, представляющими интенсивность в градациях серого в диапазоне 0-255. |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определённый для 16 бит на пиксель с 8 битами, представляющими интенсивность в градациях серого в диапазоне 0-255, и дополнительным 8‑битным альфа‑компонентом. |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | r | Получает формат пикселя. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определённый для 16 бит на пиксель с 5 битами для каждого из красного, зелёного и синего, альфа не определена. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определённый для 16 бит на пиксель с 5 битами для красного, 6 битами для зелёного и 5 битами для синего, альфа не определена. |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего, альфа не определена. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего, альфа не определена. |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для индексированного 1 бита на цвет.<br/>            Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра.<br/>            Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для индексированного 2 бита на цвет.<br/>            Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра.<br/>            Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для индексированного 4 бита на цвет.<br/>            Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра.<br/>            Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для индексированного 8 бита на цвет.<br/>            Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра.<br/>            Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для 24 бит на пиксель с 8 битами для каждого из компонентов яркости luma, разницы синего blue-difference и разницы красного red-difference. |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) определенный для 32 бит на пиксель с 8 битами для каждого из компонентов яркости luma, разницы синего blue-difference, разницы красного red-difference и черной black хромы. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | Получает цвет BGRA с указанным количеством битов на образец. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | Получает цвет BGRA с указанным количеством битов на образец. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | Получает цвет CIE Lab с указанным количеством битов на образец. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | Получает цвет CMYK с указанным количеством битов на образец. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | Получает цвет CMYK с указанным количеством битов на образец. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | Получает цвет CMYKA с указанным количеством битов на образец. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | Получает цвет Grayscale с указанным количеством битов на образец. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | Получает цвет GrayscaleAlpha с указанным количеством битов на образец. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | Получает цвет GrayscaleAlpha с указанным количеством битов на образец. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | Получает цвет RGB с указанным количеством битов на образец. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | Получает цвет RGB с указанным количеством битов на образец. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | Получает индексированный цвет BGRA с указанным количеством битов на образец. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | Получает цвет RGBA с указанным количеством битов на образец. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | Получает цвет RGBA с указанным количеством битов на образец. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | Получает цвет YCbCr с указанным количеством битов на образец. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | Получает цвет YCbCr с указанным количеством битов на образец. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | Получает цвет YCCK с указанным количеством битов на образец. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

Получает цвет BGRA с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет BGRA. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

Получает цвет BGRA с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет BGRA. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Получает цвет CIE Lab с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_l | int | Количество битов на канал L. |
| bits_per_a | int | Количество битов на канал A. |
| bits_per_b | int | Количество битов на канал B. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет CIE Lab. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Получает цвет CMYK с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_cyan_channel | int | Количество битов на канал Cyan. |
| bits_per_magenta_channel | int | Количество битов на канал Magenta. |
| bits_per_yellow_channel | int | Количество битов на канал Yellow. |
| bits_per_key_channel | int | Количество битов на канал Key. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет CMYK. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

Получает цвет CMYK с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет CMYK. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Получает цвет CMYKA с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_cyan_channel | int | Количество битов на канал Cyan. |
| bits_per_magenta_channel | int | Количество битов на канал Magenta. |
| bits_per_yellow_channel | int | Количество битов на канал Yellow. |
| bits_per_key_channel | int | Количество битов на канал Key. |
| bits_per_alpha_channel | int | Количество битов на канал Alpha. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет CMYK. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

Получает цвет Grayscale с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет Grayscale. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

Получает цвет GrayscaleAlpha с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет GrayscaleAlpha. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Получает цвет GrayscaleAlpha с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |
| alpha_channel_bits | int | Количество битов на образец в альфа-канале. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет GrayscaleAlpha. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Получает цвет RGB с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_red_channel | int | Количество битов на канал Red. |
| bits_per_green_channel | int | Количество битов на канал Green. |
| bits_per_blue_channel | int | Количество битов на канал Blue. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет RGB. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

Получает цвет RGB с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет RGB. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

Получает индексированный цвет BGRA с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Цвет BGRA. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Получает цвет RGBA с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_red_channel | int | Количество битов на канал Red. |
| bits_per_green_channel | int | Количество битов на канал Green. |
| bits_per_blue_channel | int | Количество битов на канал Blue. |
| bits_per_alpha_channel | int | Количество битов на канал Alpha. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA‑цвет. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

Получает цвет RGBA с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA‑цвет. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

Получает цвет YCbCr с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr‑цвет. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Получает цвет YCbCr с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_y | int | Количество бит в канале Y. |
| bits_per_cb | int | Количество бит в канале Cb. |
| bits_per_cr | int | Количество бит в канале Cr. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr‑цвет. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

Получает цвет YCCK с указанным количеством битов на образец.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bits_per_sample | int | Количество битов на образец. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCCK‑цвет. |


