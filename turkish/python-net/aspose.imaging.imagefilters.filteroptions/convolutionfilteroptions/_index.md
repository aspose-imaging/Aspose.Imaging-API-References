---
title: "ConvolutionFilterOptions Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | Yeni bir [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) sınıfının bir örneğini factor = 1 ve bias = 0 ile başlatır. |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | Yeni bir [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) sınıfının bir örneğini bias = 0 ile başlatır. |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | Yeni bir [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bias | int | r/w | bias değerini alır veya ayarlar. |
| borders_processing | bool | r/w | [borders processing] gösteren bir değeri alır veya ayarlar. |
| factor | float | r/w | factor değerini alır veya ayarlar. |
| ignore_alpha | bool | r/w | [ignore alpha] gösteren bir değeri alır veya ayarlar. |
| kernel_data | float[] | r | Çekirdeği alır. |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

Yeni bir [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) sınıfının bir örneğini factor = 1 ve bias = 0 ile başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| çekirdek | float[] | X ekseni yönü için konvolüsyon çekirdeği. |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

Yeni bir [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) sınıfının bir örneğini bias = 0 ile başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| çekirdek | float[] | X ekseni yönü için konvolüsyon çekirdeği. |
| factor | float | factor. |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

Yeni bir [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| çekirdek | float[] | X ekseni yönü için konvolüsyon çekirdeği. |
| factor | float | factor. |
| bias | int | bias değeri. |

