---
title: SharpenFilterOptions Class
type: docs
weight: 140
url: /python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---

**Summary:** The sharpen filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions

**Inheritance:** GaussianBlurFilterOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SharpenFilterOptions()](#SharpenFilterOptions__1) | Initializes a new instance of the [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) class. |
| [SharpenFilterOptions(size, sigma)](#SharpenFilterOptions_size_sigma_2) | Initializes a new instance of the [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Gets or sets the bias. |
| factor | float | r/w | Gets or sets the factor. |
| kernel_data | float[] | r | Gets the kernel. |
| radius | int | r/w | Gets the radius of Gausseian [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| sigma | float | r/w | Gets the Gaussian kernel sigma (smoothing). Must be a positive non-zero value. |
| size | int | r/w | Gets the Gaussian kernel size. Must be a positive non-zero odd value. |


### Constructor: SharpenFilterOptions() {#SharpenFilterOptions__1}


```
 SharpenFilterOptions() 
```

Initializes a new instance of the [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) class.

### Constructor: SharpenFilterOptions(size, sigma) {#SharpenFilterOptions_size_sigma_2}


```
 SharpenFilterOptions(size, sigma) 
```

Initializes a new instance of the [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | int | The size of the kernel. |
| sigma | float | The sigma. |

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

