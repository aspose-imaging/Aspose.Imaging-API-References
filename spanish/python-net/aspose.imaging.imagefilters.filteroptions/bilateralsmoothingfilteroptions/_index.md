---
title: "Clase BilateralSmoothingFilterOptions"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---

**Summary:** The Bilateral Smoothing Filter Options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions__1) | Inicializa una nueva instancia de la clase [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/). |
| [BilateralSmoothingFilterOptions(size)](#BilateralSmoothingFilterOptions_size_2) | Inicializa una nueva instancia de la clase [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| color_factor | float | r/w | Obtiene o establece el factor de color. |
| color_power | float | r/w | Obtiene o establece la potencia de color. |
| tamaño | int | r/w | Obtiene o establece el tamaño del kernel. |
| spatial_factor | float | r/w | Obtiene o establece el factor espacial. |
| spatial_power | float | r/w | Obtiene o establece la potencia espacial. |


### Constructor: BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions__1}


```
 BilateralSmoothingFilterOptions() 
```

Inicializa una nueva instancia de la clase [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/).

### Constructor: BilateralSmoothingFilterOptions(size) {#BilateralSmoothingFilterOptions_size_2}


```
 BilateralSmoothingFilterOptions(size) 
```

Inicializa una nueva instancia de la clase [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tamaño | int | Tamaño del kernal. |

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

