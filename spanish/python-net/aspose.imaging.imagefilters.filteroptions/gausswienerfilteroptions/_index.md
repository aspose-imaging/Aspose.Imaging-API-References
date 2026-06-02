---
title: "GaussWienerFilterOptions Clase"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener filter options for image debluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Inicializa una nueva instancia de la clase [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/). |
| [GaussWienerFilterOptions(size, sigma)](#GaussWienerFilterOptions_size_sigma_2) | Inicializa una nueva instancia de la clase [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/). |
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


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Inicializa una nueva instancia de la clase [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/).

### Constructor: GaussWienerFilterOptions(size, sigma) {#GaussWienerFilterOptions_size_sigma_2}


```
 GaussWienerFilterOptions(size, sigma) 
```

Inicializa una nueva instancia de la clase [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tamaño | int | El tamaño del kernel gaussiano. |
| sigma | float | La sigma del kernel gaussiano. |

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


## **Examples**
### The following example applies various types of filters to a raster image. {#example_59}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.imagefilters.filteroptions import *
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Aplicar un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Aplicar un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Aplicar un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Aplicar un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Aplicar un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Aplicar un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

