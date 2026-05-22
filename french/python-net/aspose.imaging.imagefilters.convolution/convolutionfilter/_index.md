---
title: "Classe ConvolutionFilter"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Obtient le noyau de flou en boîte. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Obtient le noyau de flou de mouvement. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | Obtient le noyau de relief 3x3. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | Obtient le noyau de relief 5x5. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Obtient le noyau gaussien. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | Obtient le noyau d'accentuation 3x3. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | Obtient le noyau d'accentuation 5x5. |
| [to_complex(kernel)](#to_complex_kernel_8) | Convertit _kernel_ en un noyau [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Obtient le noyau de flou en boîte.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | int | La taille du noyau. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | Le noyau de flou en boîte. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Obtient le noyau de flou de mouvement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | int | La taille du noyau. |
| angle | float | L'angle de mouvement. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | Le noyau de flou de mouvement. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

Obtient le noyau de relief 3x3.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

Obtient le noyau de relief 5x5.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Obtient le noyau gaussien.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | int | La taille du noyau. |
| sigma | float | La valeur sigma dans la plage (0...]. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | Le noyau gaussien. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

Obtient le noyau d'accentuation 3x3.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

Obtient le noyau d'accentuation 5x5.

**Returns**

| Type | Description |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

Convertit _kernel_ en un noyau [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noyau | float[] | Le noyau. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Un noyau [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


