---
title: "ConvolutionFilter-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Hämtar box‑blur‑kärnan. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Hämtar rörelse‑blur‑kärnan. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | Hämtar 3x3‑emboss‑kärnan. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | Hämtar 5x5‑emboss‑kärnan. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Hämtar Gauss‑kärnan. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | Hämtar 3x3‑skärpningskärnan. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | Hämtar 5x5‑skärpningskärnan. |
| [to_complex(kernel)](#to_complex_kernel_8) | Konverterar _kernel_ till en [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) kärna. |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Hämtar box‑blur‑kärnan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| storlek | int | Kärnans storlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] | Box‑blur‑kärnan. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Hämtar rörelse‑blur‑kärnan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| storlek | int | Kärnans storlek. |
| vinkel | float | Rörelsevinkeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] | Rörelse‑blur‑kärnan. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

Hämtar 3x3‑emboss‑kärnan.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

Hämtar 5x5‑emboss‑kärnan.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Hämtar Gauss‑kärnan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| storlek | int | Kärnans storlek. |
| sigma | float | Sigma‑värdet i intervallet (0...]. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] | Den gaussiska kärnan. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

Hämtar 3x3‑skärpningskärnan.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

Hämtar 5x5‑skärpningskärnan.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

Konverterar _kernel_ till en [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) kärna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kärna | float[] | Kärnan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | En [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) kärna. |


