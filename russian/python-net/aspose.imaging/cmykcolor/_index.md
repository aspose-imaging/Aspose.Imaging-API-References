---
title: "Класс CmykColor"
type: docs
weight: 1130
url: /ru/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Инициализирует новый экземпляр класса CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | System.Byte | r | Возвращает значение цианового компонента этой структуры [Color](/imaging/python-net/aspose.imaging/color/). |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Возвращает пустое. |
| is_empty | bool | r | Возвращает значение, указывающее, что эта структура [Color](/imaging/python-net/aspose.imaging/color/) не инициализирована. |
| k | System.Byte | r | Возвращает значение черного компонента этой структуры [Color](/imaging/python-net/aspose.imaging/color/). |
| m | System.Byte | r | Возвращает значение пурпурного компонента этой структуры [Color](/imaging/python-net/aspose.imaging/color/). |
| y | System.Byte | r | Возвращает значение желтого компонента этой структуры [Color](/imaging/python-net/aspose.imaging/color/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Создаёт структуру [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) из 32‑битных значений циана, мадженты, желтого и черного.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Преобразование из CMYKColor в 32‑битный ARGB Color с использованием ICC‑преобразования и профилей по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | Преобразование из 32-битного ARGB в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | Значение to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Инициализирует новый экземпляр класса CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Создаёт структуру [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) из 32‑битных значений циана, мадженты, желтого и черного.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

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
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Элемент [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Преобразование из CMYKColor в 32‑битный ARGB Color с использованием ICC‑преобразования и профилей по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив 32-битного цвета ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Элемент [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int[] | Пиксели 32-битного формата ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Элемент [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

Преобразование из 32-битного ARGB в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixel | int | Пиксель 32-битного формата ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Элемент [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int[] | Пиксели 32-битного формата ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Элемент [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Массив цветов ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив цветов ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Массив [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Массив [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксели типа CMYKColor в формате CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксель типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Элемент [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксель типа CMYKColor в формате CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Элемент [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив цветов ARGB. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из CMYKColor в Color с использованием icc‑конверсии.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Пиксели типа CMYKColor в формате CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль ICC RGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

Значение to.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Длинное значение CMYK. |


