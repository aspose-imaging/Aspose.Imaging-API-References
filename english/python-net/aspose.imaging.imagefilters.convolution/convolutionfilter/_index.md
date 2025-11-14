---
title: ConvolutionFilter Class
type: docs
weight: 10
url: /python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Gets the box blur kernel. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Gets the motion blur kernel. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | Gets the 3x3 Emboss kernel. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | Gets the 5x5 Emboss kernel. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Gets the Gaussian kernel. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | Gets the 3x3 sharpen kernel. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | Gets the 5x5 sharpen kernel. |
| [to_complex(kernel)](#to_complex_kernel_8) | Converts _kernel_ to a [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) kernel. |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Gets the box blur kernel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | int | The kernel size. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | The box blur kernel. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Gets the motion blur kernel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | int | The kernel size. |
| angle | float | The motion angle. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | The motion blur kernel. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

Gets the 3x3 Emboss kernel.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

Gets the 5x5 Emboss kernel.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Gets the Gaussian kernel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | int | The kernel size. |
| sigma | float | The sigma value in range (0...]. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | The Gaussian kernel. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

Gets the 3x3 sharpen kernel.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

Gets the 5x5 sharpen kernel.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

Converts _kernel_ to a [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) kernel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| kernel | float[] | The kernel. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | A [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) kernel. |


