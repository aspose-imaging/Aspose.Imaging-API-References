---
title: "Класс CmykColorHelper"
type: docs
weight: 1140
url: /ru/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | Создаёт CMYK из 32‑битных значений циана, магенты, желтого и черного. |
| [get_c(cmyk)](#get_c_cmyk_10) | Получает значение компоненты циана. |
| [get_k(cmyk)](#get_k_cmyk_11) | Получает значение компоненты черного. |
| [get_m(cmyk)](#get_m_cmyk_12) | Получает значение компоненты магенты. |
| [get_y(cmyk)](#get_y_cmyk_13) | Получает значение компоненты желтого. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | Преобразование из цветов CMYK в цвета ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | Преобразование из цветов CMYK в цвета ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | Преобразование из цветов CMYK в цвета ARGB. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | Преобразование из цветов CMYK в цвета ARGB. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | Преобразование из цвета CMYK в цвет ARGB с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | Преобразование из цвета CMYK в цвет ARGB с использованием Icc‑преобразования и пользовательского профиля. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | Преобразование из цветов CMYK в цвета ARGB. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и пользовательских профилей. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и пользовательских профилей. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и пользовательских профилей. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | Преобразование из цветов ARGB в цвета CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | Преобразование из цветов ARGB в цвета CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | Преобразование из цветов ARGB в цвета CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | Преобразование из цветов ARGB в цвета CMYK. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | Преобразование из цветов ARGB в цвета CMYK. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | Преобразует ARGB в CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | Преобразование из цвета ARGB в цвет CMYK. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | Преобразование из цветов ARGB в цвета CMYK. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Преобразует RGB в CMYK с использованием пользовательских ICC‑профилей. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | Преобразует ARGB в CMYKA (с прозрачностью). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Преобразует RGB в CMYKA (с альфа-каналом), используя пользовательские ICC‑профили. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb | int | Цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb | int | Цвет ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb | int | Цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение в порядке байтов KCMY с инвертированными значениями каналов. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | int | Цвет ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

Создаёт CMYK из 32‑битных значений циана, магенты, желтого и черного.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cyan | int | Компонент циан. Допустимые значения от 0 до 255. |
| magenta | int | Компонент мажента. Допустимые значения от 0 до 255. |
| yellow | int | Компонент желтый. Допустимые значения от 0 до 255. |
| black | int | Компонент черный. Допустимые значения от 0 до 255. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Получает значение компоненты циана.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение компонента циан. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Получает значение компоненты черного.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение компонента черный. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Получает значение компоненты магенты.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение компонента мажента. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Получает значение компоненты желтого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение желтого компонента. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

Преобразование из цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

Преобразование из цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

Преобразование из цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета ARGB представлены в виде 32‑битных целочисленных значений. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

Преобразование из цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

Преобразование из цвета CMYK в цвет ARGB с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвет ARGB. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из цвета CMYK в цвет ARGB с использованием Icc‑преобразования и пользовательского профиля.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвет ARGB. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

Преобразование из цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int[] | Пиксели CMYK представлены в виде 32‑битных целочисленных значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int[] | Пиксели CMYK представлены в виде 32‑битных целочисленных значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из цветов CMYK в цвета ARGB с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int[] | Цвета ARGB представлены в виде 32‑битных целочисленных значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int[] | Цвета ARGB представлены в виде 32‑битных целочисленных значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Преобразует ARGB в CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int[] | Цвета RGB представлены в виде 32‑битных целочисленных значений. |
| start_index | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Цвета CMYK представлены в виде массива байтов. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

Преобразование из цвета ARGB в цвет CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb | int | Цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb | int | Цвет ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Цвета ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразует RGB в CMYK с использованием пользовательских ICC‑профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета RGB представлены в виде 32‑битных целочисленных значений. |
| start_index | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |
| rgb_icc_stream | _io.BufferedRandom | Поток профиля RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток профиля CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Цвета CMYK представлены в виде массива байтов. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и пользовательских профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Преобразует ARGB в CMYKA (с прозрачностью).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int[] | Цвета RGB представлены в виде 32‑битных целочисленных значений. |
| start_index | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Цвета CMYK представлены в виде массива байтов. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразует RGB в CMYKA (с альфа-каналом), используя пользовательские ICC‑профили.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета RGB представлены в виде 32‑битных целочисленных значений. |
| start_index | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |
| rgb_icc_stream | _io.BufferedRandom | Поток профиля RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток профиля CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Цвета CMYK представлены в виде массива байтов. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

Преобразование из цвета ARGB в цвет CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb | int | Цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвет CMYK, представленный как 32‑битное целочисленное значение в порядке байтов KCMY с инвертированными значениями каналов. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и профилей по умолчанию.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование из цветов ARGB в цвета CMYK с использованием Icc‑преобразования и пользовательских профилей.<br/>            Использует формат PSD CMYK KCMY с обратным порядком байтов каналов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пиксели | int[] | Цвета ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль Icc CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Цвета CMYK, представленные как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Получить целочисленное представление черного в цветовом пространстве CMYK.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# Черный квадрат.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Нарисовать черный квадрат в центре изображения.
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

# Вывод выглядит так:
# Преобразовать RGB в CMYK без использования ICC‑профилей.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

