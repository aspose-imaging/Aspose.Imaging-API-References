---
title: "فئة ConvolutionFilter"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | يحصل على نواة تمويه الصندوق. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | يحصل على نواة تمويه الحركة. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | يحصل على نواة النقش 3x3. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | يحصل على نواة النقش 5x5. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | يحصل على النواة الغاوسية. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | يحصل على نواة الشحذ 3x3. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | يحصل على نواة الشحذ 5x5. |
| [to_complex(kernel)](#to_complex_kernel_8) | يحوّل _kernel_ إلى نواة [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

يحصل على نواة تمويه الصندوق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحجم | int | حجم النواة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] | نواة تمويه الصندوق. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

يحصل على نواة تمويه الحركة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحجم | int | حجم النواة. |
| angle | float | زاوية الحركة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] | نواة تمويه الحركة. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

يحصل على نواة النقش 3x3.

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

يحصل على نواة النقش 5x5.

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

يحصل على النواة الغاوسية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحجم | int | حجم النواة. |
| سيغما | float | قيمة سيغما في النطاق (0...]. |

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] | النواة الغاوسية. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

يحصل على نواة الشحذ 3x3.

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

يحصل على نواة الشحذ 5x5.

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

يحوّل _kernel_ إلى نواة [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| نواة | float[] | النواة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | نواة [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


