---
title: "PixelDataFormat Sınıfı"
type: docs
weight: 6920
url: /tr/python-net/aspose.imaging/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Piksel başına 16 bit olarak, gri ton yoğunluğunu temsil eden en fazla 16 bit ile tanımlanır. |
| bits_per_pixel | int | r | Piksel başına bit sayısını alır. |
| başlık | string | r | Piksel veri formatı başlığını alır. |
| channel_bits | int[] | r | Her kanal için bit sayısını alır. |
| channels_count | int | r | Kanal sayısını alır. |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Piksel başına 32 bit, cyan, magenta, yellow ve black için her birine 8 bit olmak üzere tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | acmyk'yi alır. |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r/w | Piksel başına 8 bit, 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ile tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Piksel başına 16 bit, 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni ile tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | r | Piksel formatını alır. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Piksel başına 16 bit, kırmızı, yeşil ve mavi için her birine 5 bit olmak üzere tanımlanan ve alfa tanımlanmamış [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Piksel başına 16 bit, kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit olmak üzere tanımlanan ve alfa tanımlanmamış [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 24 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır, alfa tanımlı değildir. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 24 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır, alfa tanımlı değildir. |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Renk başına indeksli 1 bit için tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Renk başına indeksli 2 bit için tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Renk başına indeksli 4 bit için tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Renk başına indeksli 8 bit için tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 24 bit piksel başına, luma, mavi-fark ve kırmızı-fark renk doygunluğu bileşenleri için her biri 8 bit olmak üzere tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 32 bit piksel başına, luma, mavi-fark, kırmızı-fark ve siyah renk doygunluğu bileşenleri için her biri 8 bit olmak üzere tanımlanan [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | Örnek başına belirtilen bit sayısıyla BGRA rengini alır. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | Örnek başına belirtilen bit sayısıyla BGRA rengini alır. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | Örnek başına belirtilen bit sayısıyla CIE Lab rengini alır. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | Örnek başına belirtilen bit sayısıyla CMYK rengini alır. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | Örnek başına belirtilen bit sayısıyla CMYK rengini alır. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | Örnek başına belirtilen bit sayısıyla CMYKA rengini alır. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | Örnek başına belirtilen bit sayısıyla Grayscale rengini alır. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | Örnek başına belirtilen bit sayısıyla GrayscaleAlpha rengini alır. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | Örnek başına belirtilen bit sayısıyla GrayscaleAlpha rengini alır. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | Örnek başına belirtilen bit sayısıyla RGB rengini alır. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | Örnek başına belirtilen bit sayısıyla RGB rengini alır. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | Örnek başına belirtilen bit sayısıyla BGRA indeksli rengini alır. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | Örnek başına belirtilen bit sayısıyla RGBA rengini alır. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | Örnek başına belirtilen bit sayısıyla RGBA rengini alır. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | Örnek başına belirtilen bit sayısıyla YCbCr rengini alır. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | Örnek başına belirtilen bit sayısıyla YCbCr rengini alır. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | Örnek başına belirtilen bit sayısıyla YCCK rengini alır. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla BGRA rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA rengi. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla BGRA rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA rengi. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Örnek başına belirtilen bit sayısıyla CIE Lab rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_l | int | L kanalı başına bit sayısı. |
| bits_per_a | int | A kanalı başına bit sayısı. |
| bits_per_b | int | B kanalındaki bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CIE Lab rengi. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Örnek başına belirtilen bit sayısıyla CMYK rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan kanalındaki bit sayısı. |
| bits_per_magenta_channel | int | Magenta kanalındaki bit sayısı. |
| bits_per_yellow_channel | int | Yellow kanalındaki bit sayısı. |
| bits_per_key_channel | int | Key kanalındaki bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK rengi. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla CMYK rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK rengi. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Örnek başına belirtilen bit sayısıyla CMYKA rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan kanalındaki bit sayısı. |
| bits_per_magenta_channel | int | Magenta kanalındaki bit sayısı. |
| bits_per_yellow_channel | int | Yellow kanalındaki bit sayısı. |
| bits_per_key_channel | int | Key kanalındaki bit sayısı. |
| bits_per_alpha_channel | int | Alpha kanalındaki bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK rengi. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla Grayscale rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Gri tonlamalı renk. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla GrayscaleAlpha rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Gri tonlamalı Alfa rengi. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Örnek başına belirtilen bit sayısıyla GrayscaleAlpha rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |
| alpha_channel_bits | int | Alfa kanalındaki örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Gri tonlamalı Alfa rengi. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Örnek başına belirtilen bit sayısıyla RGB rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_red_channel | int | Red kanalındaki bit sayısı. |
| bits_per_green_channel | int | Green kanalındaki bit sayısı. |
| bits_per_blue_channel | int | Blue kanalındaki bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGB rengi. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla RGB rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGB rengi. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla BGRA indeksli rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA rengi. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Örnek başına belirtilen bit sayısıyla RGBA rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_red_channel | int | Red kanalındaki bit sayısı. |
| bits_per_green_channel | int | Green kanalındaki bit sayısı. |
| bits_per_blue_channel | int | Blue kanalındaki bit sayısı. |
| bits_per_alpha_channel | int | Alpha kanalındaki bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA rengi. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla RGBA rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA rengi. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla YCbCr rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr rengi. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Örnek başına belirtilen bit sayısıyla YCbCr rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_y | int | Y kanalındaki bit sayısı. |
| bits_per_cb | int | Cb kanalındaki bit sayısı. |
| bits_per_cr | int | Cr kanalındaki bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr rengi. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

Örnek başına belirtilen bit sayısıyla YCCK rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCCK rengi. |


