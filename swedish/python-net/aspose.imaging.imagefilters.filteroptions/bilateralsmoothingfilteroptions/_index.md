---
title: "BilateralSmoothingFilterOptions klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---

**Summary:** The Bilateral Smoothing Filter Options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions__1) | Initierar en ny instans av [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) klass. |
| [BilateralSmoothingFilterOptions(size)](#BilateralSmoothingFilterOptions_size_2) | Initierar en ny instans av [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_factor | float | r/w | Hämtar eller anger färgfaktorn. |
| color_power | float | r/w | Hämtar eller anger färgstyrkan. |
| storlek | int | r/w | Hämtar eller anger storleken på kärnan. |
| spatial_factor | float | r/w | Hämtar eller anger rumslig faktor. |
| spatial_power | float | r/w | Hämtar eller anger rumslig effekt. |


### Constructor: BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions__1}


```
 BilateralSmoothingFilterOptions() 
```

Initierar en ny instans av [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) klass.

### Constructor: BilateralSmoothingFilterOptions(size) {#BilateralSmoothingFilterOptions_size_2}


```
 BilateralSmoothingFilterOptions(size) 
```

Initierar en ny instans av [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| storlek | int | Storlek på kärnan. |

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

