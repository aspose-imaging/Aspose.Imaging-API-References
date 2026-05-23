---
title: "Clase GaussianDeconvolutionFilterOptions"
type: docs
weight: 110
url: /es/python-net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---

**Summary:** The deconvolution filter options using Gaussian bluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions

**Inheritance:** DeconvolutionFilterOptions

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brillo | float | r/w | Obtiene o establece el brillo.<br/>            rango recomendado 1 - 1.5<br/>            valor predeterminado = 1.15 |
| grayscale | bool | r/w | Obtiene o establece un valor que indica si este [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) está en escala de grises.<br/>            Devuelve modo escala de grises o modo RGB. |
| is_partial_loaded | bool | r | Obtiene un valor que indica si esta instancia está parcialmente cargada. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Obtiene el kernel. |
| radius | int | r/w | Obtiene el radio del kernel gaussiano [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| sigma | float | r/w | Obtiene la sigma del kernel gaussiano (suavizado). Debe ser un valor positivo distinto de cero. |
| tamaño | int | r/w | Obtiene el tamaño del kernel gaussiano. Debe ser un valor impar positivo distinto de cero. |
| snr | float | r/w | Obtiene o establece la SNR (relación señal-ruido)<br/>            rango recomendado 0.002 - 0.009, valor predeterminado = 0.007 |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El kernel Complex[]. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| kernel | float[] | El kernel double[]. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


