---
title: "SharpenFilterOptions klass"
type: docs
weight: 160
url: /sv/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---

**Summary:** The sharpen filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions

**Inheritance:** GaussianBlurFilterOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SharpenFilterOptions()](#SharpenFilterOptions__1) | Initierar en ny instans av klassen [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/). |
| [SharpenFilterOptions(size, sigma)](#SharpenFilterOptions_size_sigma_2) | Initierar en ny instans av klassen [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Hämtar eller anger bias. |
| borders_processing | bool | r/w | Hämtar eller anger ett värde som indikerar om [borders processing]. |
| factor | float | r/w | Hämtar eller anger faktorn. |
| ignore_alpha | bool | r/w | Hämtar eller anger ett värde som indikerar om [ignore alpha]. |
| kernel_data | float[] | r | Hämtar kärnan. |
| radius | int | r/w | Hämtar radien för den Gaussiska [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| sigma | float | r/w | Hämtar sigma för det Gaussiska filtret (utjämning). Måste vara ett positivt icke‑nollvärde. |
| storlek | int | r/w | Hämtar storleken på det Gaussiska filtret. Måste vara ett positivt, icke‑noll, udda värde. |


### Constructor: SharpenFilterOptions() {#SharpenFilterOptions__1}


```
 SharpenFilterOptions() 
```

Initierar en ny instans av klassen [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/).

### Constructor: SharpenFilterOptions(size, sigma) {#SharpenFilterOptions_size_sigma_2}


```
 SharpenFilterOptions(size, sigma) 
```

Initierar en ny instans av klassen [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| storlek | int | Kärnans storlek. |
| sigma | float | Sigma. |

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
	# Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett slätningsvärde på 4,0 på hela bilden.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applicera ett rörelse‑Wiener-filter med en längd på 5, ett slätningsvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applicera ett skärpefilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

