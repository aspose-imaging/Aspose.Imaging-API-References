---
title: "ConvolutionFilterOptions Classe"
type: docs
weight: 60
url: /fr/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) avec factor = 1, et bias = 0. |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) avec bias = 0. |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Obtient ou définit le bias. |
| borders_processing | bool | r/w | Obtient ou définit une valeur indiquant si [borders processing]. |
| factor | float | r/w | Obtient ou définit le factor. |
| ignore_alpha | bool | r/w | Obtient ou définit une valeur indiquant si [ignore alpha]. |
| kernel_data | float[] | r | Obtient le noyau. |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) avec factor = 1, et bias = 0.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noyau | float[] | Le noyau de convolution pour la direction de l'axe X. |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) avec bias = 0.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noyau | float[] | Le noyau de convolution pour la direction de l'axe X. |
| factor | float | Le factor. |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noyau | float[] | Le noyau de convolution pour la direction de l'axe X. |
| factor | float | Le factor. |
| bias | int | La valeur du bias. |

