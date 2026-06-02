---
title: "ConvolutionFilterOptions Clase"
type: docs
weight: 60
url: /es/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) con factor = 1 y sesgo = 0. |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) con sesgo = 0. |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| sesgo | int | r/w | Obtiene o establece el sesgo. |
| borders_processing | bool | r/w | Obtiene o establece un valor que indica si [borders processing]. |
| factor | float | r/w | Obtiene o establece el factor. |
| ignore_alpha | bool | r/w | Obtiene o establece un valor que indica si [ignore alpha]. |
| kernel_data | float[] | r | Obtiene el kernel. |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) con factor = 1 y sesgo = 0.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| kernel | float[] | El kernel de convolución para la dirección del eje X. |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) con sesgo = 0.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| kernel | float[] | El kernel de convolución para la dirección del eje X. |
| factor | float | El factor. |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| kernel | float[] | El kernel de convolución para la dirección del eje X. |
| factor | float | El factor. |
| sesgo | int | El valor del sesgo. |

