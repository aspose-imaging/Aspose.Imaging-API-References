---
title: "Classe MotionWienerFilterOptions"
type: docs
weight: 140
url: /fr/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** The motion debluring filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MotionWienerFilterOptions(size, sigma, angle)](#MotionWienerFilterOptions_size_sigma_angle_1) | Initialise une nouvelle instance de la classe [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtient ou définit l'angle en degrés. |
| luminosité | float | r/w | Obtient ou définit la luminosité.<br/>            plage recommandée 1 - 1.5<br/>            valeur par défaut = 1.15 |
| grayscale | bool | r/w | Obtient ou définit une valeur indiquant si ce [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) est en niveaux de gris.<br/>            Retourne le mode niveaux de gris ou le mode RGB. |
| is_partial_loaded | bool | r | Obtient une valeur indiquant si cette instance est partiellement chargée. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Obtient le noyau. |
| radius | int | r/w | Obtient le rayon du [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/) gaussien. |
| sigma | float | r/w | Obtient le sigma du noyau gaussien (lissage). Doit être une valeur positive non nulle. |
| size | int | r/w | Obtient la taille du noyau gaussien. Doit être une valeur impaire positive non nulle. |
| snr | float | r/w | Obtient ou définit le SNR (rapport signal/bruit)<br/>            plage recommandée 0.002 - 0.009, valeur par défaut = 0.007 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Constructor: MotionWienerFilterOptions(size, sigma, angle) {#MotionWienerFilterOptions_size_sigma_angle_1}


```
 MotionWienerFilterOptions(size, sigma, angle) 
```

Initialise une nouvelle instance de la classe [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | int | La taille du noyau gaussien. |
| sigma | float | Le sigma du noyau gaussien. |
| angle | float | L'angle en degrés. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le noyau Complex[]. |

**Returns**

| Type | Description |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noyau | float[] | Le noyau double[]. |

**Returns**

| Type | Description |
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

