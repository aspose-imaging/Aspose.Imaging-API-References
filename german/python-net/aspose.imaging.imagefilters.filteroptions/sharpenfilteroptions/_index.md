---
title: "SharpenFilterOptions Klasse"
type: docs
weight: 160
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---

**Summary:** The sharpen filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions

**Inheritance:** GaussianBlurFilterOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SharpenFilterOptions()](#SharpenFilterOptions__1) | Initialisiert eine neue Instanz der [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) Klasse. |
| [SharpenFilterOptions(size, sigma)](#SharpenFilterOptions_size_sigma_2) | Initialisiert eine neue Instanz der [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bias | int | r/w | Liest oder setzt den bias. |
| borders_processing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [borders processing]. |
| factor | float | r/w | Liest oder setzt den factor. |
| ignore_alpha | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [ignore alpha]. |
| kernel_data | float[] | r | Liest den Kernel. |
| radius | int | r/w | Liest den Radius des gaußschen [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| Sigma | float | r/w | Liest das Sigma des Gauß‑Kernels (Glättung). Muss ein positiver, von Null verschiedener Wert sein. |
| size | int | r/w | Liest die Größe des Gauß‑Kernels. Muss ein positiver, von Null verschiedener, ungerader Wert sein. |


### Constructor: SharpenFilterOptions() {#SharpenFilterOptions__1}


```
 SharpenFilterOptions() 
```

Initialisiert eine neue Instanz der [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) Klasse.

### Constructor: SharpenFilterOptions(size, sigma) {#SharpenFilterOptions_size_sigma_2}


```
 SharpenFilterOptions(size, sigma) 
```

Initialisiert eine neue Instanz der [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | int | Die Größe des Kerns. |
| Sigma | float | Das Sigma. |

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
	# Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Gaußschen Unschärfefilter mit einem Radius von 5 und einem Sigma‑Wert von 4,0 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Gauss‑Wiener‑Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Bewegungs‑Wiener‑Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma‑Wert von 4,0 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

