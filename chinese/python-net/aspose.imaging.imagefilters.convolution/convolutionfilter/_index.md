---
title: "ConvolutionFilter 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | 获取盒式模糊核。 |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | 获取运动模糊核。 |
| [get_emboss_3x3()](#get_emboss_3x3__3) | 获取 3x3 浮雕核。 |
| [get_emboss_5x5()](#get_emboss_5x5__4) | 获取 5x5 浮雕核。 |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | 获取高斯核。 |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | 获取 3x3 锐化核。 |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | 获取 5x5 锐化核。 |
| [to_complex(kernel)](#to_complex_kernel_8) | 将 _kernel_ 转换为 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 核。 |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

获取盒式模糊核。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | int | 核大小。 |

**Returns**

| Type | Description |
| :- | :- |
| float[] | 盒式模糊核。 |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

获取运动模糊核。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | int | 核大小。 |
| 角度 | float | 运动角度。 |

**Returns**

| Type | Description |
| :- | :- |
| float[] | 运动模糊核。 |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

获取 3x3 浮雕核。

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

获取 5x5 浮雕核。

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

获取高斯核。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | int | 核大小。 |
| sigma | float | 范围 (0...] 内的 sigma 值。 |

**Returns**

| Type | Description |
| :- | :- |
| float[] | Gaussian 核。 |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

获取 3x3 锐化核。

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

获取 5x5 锐化核。

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

将 _kernel_ 转换为 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 核。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 核 | float[] | 该核。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 一个 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 核。 |


