---
title: "Classe ConvolutionFilter"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Ottiene il kernel di sfocatura a scatola. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Ottiene il kernel di sfocatura di movimento. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | Ottiene il kernel Emboss 3x3. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | Ottiene il kernel Emboss 5x5. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Ottiene il kernel gaussiano. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | Ottiene il kernel sharpen 3x3. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | Ottiene il kernel sharpen 5x5. |
| [to_complex(kernel)](#to_complex_kernel_8) | Converte _kernel_ in un kernel [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Ottiene il kernel di sfocatura a scatola.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | La dimensione del kernel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] | Il kernel di sfocatura a scatola. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Ottiene il kernel di sfocatura di movimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | La dimensione del kernel. |
| angle | float | L'angolo di movimento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] | Il kernel di sfocatura di movimento. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

Ottiene il kernel Emboss 3x3.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

Ottiene il kernel Emboss 5x5.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Ottiene il kernel gaussiano.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | La dimensione del kernel. |
| sigma | float | Il valore sigma nell'intervallo (0...]. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] | Il kernel gaussiano. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

Ottiene il kernel sharpen 3x3.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

Ottiene il kernel sharpen 5x5.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

Converte _kernel_ in un kernel [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| kernel | float[] | Il kernel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) kernel. |


