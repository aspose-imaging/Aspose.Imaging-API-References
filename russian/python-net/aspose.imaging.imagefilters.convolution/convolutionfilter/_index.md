---
title: "Класс ConvolutionFilter"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Получает ядро размытия коробкой. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Получает ядро размытия движения. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | Получает 3x3 ядро рельефа. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | Получает 5x5 ядро рельефа. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Получает гауссово ядро. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | Получает 3x3 ядро резкости. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | Получает 5x5 ядро резкости. |
| [to_complex(kernel)](#to_complex_kernel_8) | Преобразует _kernel_ в [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) ядро. |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Получает ядро размытия коробкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | int | Размер ядра. |

**Returns**

| Тип | Описание |
| :- | :- |
| float[] | Ядро размытия коробкой. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Получает ядро размытия движения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | int | Размер ядра. |
| угол | float | Угол движения. |

**Returns**

| Тип | Описание |
| :- | :- |
| float[] | Ядро размытия движения. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

Получает 3x3 ядро рельефа.

**Returns**

| Тип | Описание |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

Получает 5x5 ядро рельефа.

**Returns**

| Тип | Описание |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Получает гауссово ядро.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | int | Размер ядра. |
| сигма | float | Значение сигмы в диапазоне (0...]. |

**Returns**

| Тип | Описание |
| :- | :- |
| float[] | Гауссово ядро. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

Получает 3x3 ядро резкости.

**Returns**

| Тип | Описание |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

Получает 5x5 ядро резкости.

**Returns**

| Тип | Описание |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

Преобразует _kernel_ в [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) ядро.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ядро | float[] | Ядро. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Ядро [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


