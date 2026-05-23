---
title: "GaussianDeconvolutionFilterOptions Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---

**Summary:** The deconvolution filter options using Gaussian bluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions

**Inheritance:** DeconvolutionFilterOptions

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| parlaklık | float | r/w | Parlaklığı alır veya ayarlar.<br/>            önerilen aralık 1 - 1.5<br/>            varsayılan değer = 1.15 |
| grayscale | bool | r/w | Bu [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) nesnesinin gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Gri tonlamalı mod veya RGB modunu döndürür. |
| is_partial_loaded | bool | r | Bu örneğin kısmen yüklendiğini gösteren bir değeri alır. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Çekirdeği alır. |
| radius | int | r/w | Gaussian [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/) yarıçapını alır. |
| sigma | float | r/w | Gaussian çekirdek sigma değerini (yumuşatma) alır. Pozitif sıfır olmayan bir değer olmalıdır. |
| size | int | r/w | Gaussian çekirdek boyutunu alır. Pozitif sıfır olmayan tek bir değer olmalıdır. |
| snr | float | r/w | SNR (signal-to-noise ratio) değerini alır veya ayarlar.<br/>            önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007 |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır. |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır. |


### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Complex[] çekirdeği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| çekirdek | float[] | double[] çekirdeği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


