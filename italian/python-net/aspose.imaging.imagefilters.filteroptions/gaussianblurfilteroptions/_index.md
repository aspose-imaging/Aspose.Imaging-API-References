---
title: "Classe GaussianBlurFilterOptions"
type: docs
weight: 100
url: /it/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---

**Summary:** The Gaussian blur filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions

**Inheritance:** ConvolutionFilterOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions__1) | Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/). |
| [GaussianBlurFilterOptions(size, sigma)](#GaussianBlurFilterOptions_size_sigma_2) | Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bias | int | r/w | Ottiene o imposta il bias. |
| borders_processing | bool | r/w | Ottiene o imposta un valore che indica se [borders processing]. |
| factor | float | r/w | Ottiene o imposta il factor. |
| ignore_alpha | bool | r/w | Ottiene o imposta un valore che indica se [ignore alpha]. |
| kernel_data | float[] | r | Ottiene il kernel gaussiano. |
| radius | int | r/w | Restituisce il raggio del kernel gaussiano [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| sigma | float | r/w | Restituisce la sigma del kernel gaussiano (sfumatura). Deve essere un valore positivo diverso da zero. |
| dimensione | int | r/w | Restituisce la dimensione del kernel gaussiano. Deve essere un valore dispari positivo diverso da zero. |


### Constructor: GaussianBlurFilterOptions() {#GaussianBlurFilterOptions__1}


```
 GaussianBlurFilterOptions() 
```

Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/).

### Constructor: GaussianBlurFilterOptions(size, sigma) {#GaussianBlurFilterOptions_size_sigma_2}


```
 GaussianBlurFilterOptions(size, sigma) 
```

Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | La dimensione del kernel Gaussian.. |
| sigma | float | La sigma del kernel gaussiano. |

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
	# Applica un filtro mediano con una dimensione del rettangolo pari a 5 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro di levigatura bilaterale con una dimensione del kernel pari a 5 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90,0 gradi all'intera immagine.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro di nitidezza con una dimensione del kernel pari a 5 e un valore sigma di 4.0 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

