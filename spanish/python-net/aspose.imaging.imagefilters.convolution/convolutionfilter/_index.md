---
title: "Clase ConvolutionFilter"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Obtiene el kernel de desenfoque de caja. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Obtiene el kernel de desenfoque de movimiento. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | Obtiene el kernel de relieve 3x3. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | Obtiene el kernel de relieve 5x5. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Obtiene el kernel gaussiano. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | Obtiene el kernel de afilado 3x3. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | Obtiene el kernel de afilado 5x5. |
| [to_complex(kernel)](#to_complex_kernel_8) | Convierte _kernel_ a un kernel [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Obtiene el kernel de desenfoque de caja.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tamaño | int | El tamaño del kernel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] | El kernel de desenfoque de caja. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Obtiene el kernel de desenfoque de movimiento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tamaño | int | El tamaño del kernel. |
| angle | float | El ángulo de movimiento. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] | El kernel de desenfoque de movimiento. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

Obtiene el kernel de relieve 3x3.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

Obtiene el kernel de relieve 5x5.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Obtiene el kernel gaussiano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tamaño | int | El tamaño del kernel. |
| sigma | float | El valor sigma en el rango (0...]. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] | El kernel gaussiano. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

Obtiene el kernel de afilado 3x3.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

Obtiene el kernel de afilado 5x5.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

Convierte _kernel_ a un kernel [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| kernel | float[] | El kernel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Un kernel [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


