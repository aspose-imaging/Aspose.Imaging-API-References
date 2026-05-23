---
title: "ConvolutionFilterOptions Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | Initialisiert eine neue Instanz der [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) Klasse mit factor = 1 und bias = 0. |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | Initialisiert eine neue Instanz der [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) Klasse mit bias = 0. |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | Initialisiert eine neue Instanz der [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bias | int | r/w | Liest oder setzt den bias. |
| borders_processing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [borders processing]. |
| factor | float | r/w | Liest oder setzt den factor. |
| ignore_alpha | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [ignore alpha]. |
| kernel_data | float[] | r | Liest den Kernel. |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

Initialisiert eine neue Instanz der [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) Klasse mit factor = 1 und bias = 0.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kernel | float[] | Der Convolution-Kernel für die X-Achsen-Richtung. |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

Initialisiert eine neue Instanz der [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) Klasse mit bias = 0.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kernel | float[] | Der Convolution-Kernel für die X-Achsen-Richtung. |
| factor | float | Der factor. |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

Initialisiert eine neue Instanz der [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kernel | float[] | Der Convolution-Kernel für die X-Achsen-Richtung. |
| factor | float | Der factor. |
| bias | int | Der bias-Wert. |

