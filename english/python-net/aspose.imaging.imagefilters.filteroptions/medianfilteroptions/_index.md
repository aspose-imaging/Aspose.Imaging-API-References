---
title: MedianFilterOptions Class
type: docs
weight: 130
url: /python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---

**Summary:** Median filter

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MedianFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MedianFilterOptions(size)](#MedianFilterOptions_size_1) | Initializes a new instance of the [MedianFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Gets or sets the size. |


### Constructor: MedianFilterOptions(size) {#MedianFilterOptions_size_1}


```
 MedianFilterOptions(size) 
```

Initializes a new instance of the [MedianFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | int | The size of filter rectangle. |

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
	# Apply a median filter with a rectangle size of 5 to the entire image.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Apply a bilateral smoothing filter with a kernel size of 5 to the entire image.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Apply a Gaussian blur filter with a radius of 5 and a sigma value of 4.0 to the entire image.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Apply a Gauss-Wiener filter with a radius of 5 and a smooth value of 4.0 to the entire image.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Apply a motion wiener filter with a length of 5, a smooth value of 4.0 and an angle of 90.0 degrees to the entire image.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Apply a sharpen filter with a kernel size of 5 and a sigma value of 4.0 to the entire image.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

