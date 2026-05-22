---
title: "GaussianBlurFilterOptions Classe"
type: docs
weight: 100
url: /fr/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---

**Summary:** The Gaussian blur filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions

**Inheritance:** ConvolutionFilterOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions__1) | Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/). |
| [GaussianBlurFilterOptions(size, sigma)](#GaussianBlurFilterOptions_size_sigma_2) | Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Obtient ou définit le bias. |
| borders_processing | bool | r/w | Obtient ou définit une valeur indiquant si [borders processing]. |
| factor | float | r/w | Obtient ou définit le factor. |
| ignore_alpha | bool | r/w | Obtient ou définit une valeur indiquant si [ignore alpha]. |
| kernel_data | float[] | r | Obtient le noyau gaussien. |
| radius | int | r/w | Obtient le rayon du [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/) gaussien. |
| sigma | float | r/w | Obtient le sigma du noyau gaussien (lissage). Doit être une valeur positive non nulle. |
| size | int | r/w | Obtient la taille du noyau gaussien. Doit être une valeur impaire positive non nulle. |


### Constructor: GaussianBlurFilterOptions() {#GaussianBlurFilterOptions__1}


```
 GaussianBlurFilterOptions() 
```

Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/).

### Constructor: GaussianBlurFilterOptions(size, sigma) {#GaussianBlurFilterOptions_size_sigma_2}


```
 GaussianBlurFilterOptions(size, sigma) 
```

Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | int | La taille du noyau Gaussien.. |
| sigma | float | Le sigma du noyau gaussien. |

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
	# Appliquez un filtre médian avec une taille de rectangle de 5 à l'image entière.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'image entière.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'image entière.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'image entière.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'image entière.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'image entière.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

