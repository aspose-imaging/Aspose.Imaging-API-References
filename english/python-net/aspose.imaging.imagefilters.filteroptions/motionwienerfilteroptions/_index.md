---
title: MotionWienerFilterOptions Class
type: docs
weight: 90
url: /python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** Deconvolution filter options<br/>                deblur motion

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.Imaging Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MotionWienerFilterOptions(length, smooth, angle)](#MotionWienerFilterOptions_length_smooth_angle_1) | Initializes a new instance of the [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | double | r/w | Gets or sets the angle in gradus. |
| brightness | double | r/w | Gets or sets the brightness.<br/>            recommended range 1 - 1.5<br/>            default value = 1.15 |
| grayscale | bool | r/w | Gets or sets a value indicating whether this [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) is grayscale.<br/>            Return grayscale mode or RGB mode. |
| is_partial_loaded | bool | r | Gets a value indicating whether this instance is partial loaded. |
| length | int | r/w | Gets or sets the length. |
| smooth | double | r/w | Gets or sets the smooth. |
| snr | double | r/w | Gets or sets the SNR(signal-to-noise ratio)<br/>            recommended range 0.002 - 0.009, default value = 0.007 |


### Constructor: MotionWienerFilterOptions(length, smooth, angle) {#MotionWienerFilterOptions_length_smooth_angle_1}


```
 MotionWienerFilterOptions(length, smooth, angle) 
```

Initializes a new instance of the [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| length | int | The length. |
| smooth | double | The smooth. |
| angle | double | The angle in gradus. |

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

