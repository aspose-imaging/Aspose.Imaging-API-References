---
title: "MotionWienerFilterOptions-klass"
type: docs
weight: 140
url: /sv/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** The motion debluring filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MotionWienerFilterOptions(size, sigma, angle)](#MotionWienerFilterOptions_size_sigma_angle_1) | Initierar en ny instans av klassen [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| vinkel | float | r/w | Hämtar eller anger vinkeln i grader. |
| ljusstyrka | float | r/w | Hämtar eller anger ljusstyrkan.<br/>            rekommenderat intervall 1 - 1.5<br/>            standardvärde = 1.15 |
| grayscale | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) är i gråskala.<br/>            Returnerar gråskaleläge eller RGB-läge. |
| is_partial_loaded | bool | r | Hämtar ett värde som indikerar om denna instans är delvis inläst. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Hämtar kärnan. |
| radius | int | r/w | Hämtar radien för den Gaussiska [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| sigma | float | r/w | Hämtar sigma för det Gaussiska filtret (utjämning). Måste vara ett positivt icke‑nollvärde. |
| storlek | int | r/w | Hämtar storleken på det Gaussiska filtret. Måste vara ett positivt, icke‑noll, udda värde. |
| snr | float | r/w | Hämtar eller anger SNR (signal‑till‑brus‑förhållande)<br/>            rekommenderat intervall 0.002 - 0.009, standardvärde = 0.007 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Initierar en ny instans av klassen [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Initierar en ny instans av klassen [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Constructor: MotionWienerFilterOptions(size, sigma, angle) {#MotionWienerFilterOptions_size_sigma_angle_1}


```
 MotionWienerFilterOptions(size, sigma, angle) 
```

Initierar en ny instans av klassen [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| storlek | int | Den Gaussiska filterkärnans storlek. |
| sigma | float | Den Gaussiska filterkärnans sigma. |
| vinkel | float | Vinkeln i grader. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Initierar en ny instans av klassen [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den Complex[]-kärnan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Initierar en ny instans av klassen [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kärna | float[] | Den double[]-kärnan. |

**Returns**

| Typ | Beskrivning |
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

