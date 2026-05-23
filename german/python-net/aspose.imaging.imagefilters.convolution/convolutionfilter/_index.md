---
title: "ConvolutionFilter Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Liefert den Box-Blur-Kernel. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Liefert den Motion-Blur-Kernel. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | Liefert den 3x3-Emboss-Kernel. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | Liefert den 5x5-Emboss-Kernel. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Liefert den Gaußschen Kernel. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | Liefert den 3x3-Schärfungs-Kernel. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | Liefert den 5x5-Schärfungs-Kernel. |
| [to_complex(kernel)](#to_complex_kernel_8) | Konvertiert _kernel_ zu einem [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) Kernel. |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Liefert den Box-Blur-Kernel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | int | Die Kernelgröße. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] | Der Box-Blur-Kernel. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Liefert den Motion-Blur-Kernel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | int | Die Kernelgröße. |
| angle | float | Der Bewegungswinkel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] | Der Motion-Blur-Kernel. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

Liefert den 3x3-Emboss-Kernel.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

Liefert den 5x5-Emboss-Kernel.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Liefert den Gaußschen Kernel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | int | Die Kernelgröße. |
| Sigma | float | Der Sigma-Wert im Bereich (0...]. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] | Der Gaußsche Kernel. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

Liefert den 3x3-Schärfungs-Kernel.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

Liefert den 5x5-Schärfungs-Kernel.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

Konvertiert _kernel_ zu einem [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) Kernel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kernel | float[] | Der Kernel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Ein [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) Kernel. |


