---
title: "ConvolutionFilter Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.imagefilters.convolution/convolutionfilter/
---

**Summary:** The kernel matrix provider class.

**Module:** [aspose.imaging.imagefilters.convolution](/imaging/python-net/aspose.imaging.imagefilters.convolution/)

**Full Name:** aspose.imaging.imagefilters.convolution.ConvolutionFilter

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_blur_box(size)](#get_blur_box_size_1) | Kutu bulanıklaştırma çekirdeğini alır. |
| [get_blur_motion(size, angle)](#get_blur_motion_size_angle_2) | Hareket bulanıklaştırma çekirdeğini alır. |
| [get_emboss_3x3()](#get_emboss_3x3__3) | 3x3 Kabartma çekirdeğini alır. |
| [get_emboss_5x5()](#get_emboss_5x5__4) | 5x5 Kabartma çekirdeğini alır. |
| [get_gaussian(size, sigma)](#get_gaussian_size_sigma_5) | Gaussian çekirdeğini alır. |
| [get_sharpen_3x3()](#get_sharpen_3x3__6) | 3x3 Keskinleştirme çekirdeğini alır. |
| [get_sharpen_5x5()](#get_sharpen_5x5__7) | 5x5 Keskinleştirme çekirdeğini alır. |
| [to_complex(kernel)](#to_complex_kernel_8) | _kernel_'ı bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) çekirdeğine dönüştürür. |


### Method: get_blur_box(size)  [static] {#get_blur_box_size_1}


```
 get_blur_box(size) 
```

Kutu bulanıklaştırma çekirdeğini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | int | Çekirdek boyutu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] | Kutu bulanıklaştırma çekirdeği. |


### Method: get_blur_motion(size, angle)  [static] {#get_blur_motion_size_angle_2}


```
 get_blur_motion(size, angle) 
```

Hareket bulanıklaştırma çekirdeğini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | int | Çekirdek boyutu. |
| angle | float | Hareket açısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] | Hareket bulanıklaştırma çekirdeği. |


### Method: get_emboss_3x3()  [static] {#get_emboss_3x3__3}


```
 get_emboss_3x3() 
```

3x3 Kabartma çekirdeğini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] |  |


### Method: get_emboss_5x5()  [static] {#get_emboss_5x5__4}


```
 get_emboss_5x5() 
```

5x5 Kabartma çekirdeğini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] |  |


### Method: get_gaussian(size, sigma)  [static] {#get_gaussian_size_sigma_5}


```
 get_gaussian(size, sigma) 
```

Gaussian çekirdeğini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | int | Çekirdek boyutu. |
| sigma | float | Aralık (0...]) içindeki sigma değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] | Gaussian çekirdeği. |


### Method: get_sharpen_3x3()  [static] {#get_sharpen_3x3__6}


```
 get_sharpen_3x3() 
```

3x3 Keskinleştirme çekirdeğini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] |  |


### Method: get_sharpen_5x5()  [static] {#get_sharpen_5x5__7}


```
 get_sharpen_5x5() 
```

5x5 Keskinleştirme çekirdeğini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] |  |


### Method: to_complex(kernel)  [static] {#to_complex_kernel_8}


```
 to_complex(kernel) 
```

_kernel_'ı bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) çekirdeğine dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| çekirdek | float[] | Çekirdek. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) çekirdek. |


