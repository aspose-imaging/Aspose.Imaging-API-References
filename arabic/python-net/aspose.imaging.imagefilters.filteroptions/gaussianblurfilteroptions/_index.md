---
title: "فئة GaussianBlurFilterOptions"
type: docs
weight: 100
url: /ar/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---

**Summary:** The Gaussian blur filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions

**Inheritance:** ConvolutionFilterOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions__1) | ينشئ مثيلاً جديداً للفئة [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/). |
| [GaussianBlurFilterOptions(size, sigma)](#GaussianBlurFilterOptions_size_sigma_2) | ينشئ مثيلاً جديداً للفئة [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| التحيز | int | r/w | يحصل أو يضبط التحيز. |
| borders_processing | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [borders processing]. |
| العامل | float | r/w | يحصل أو يضبط العامل. |
| ignore_alpha | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [ignore alpha]. |
| kernel_data | float[] | r | يحصل على النواة الغاوسية. |
| radius | int | r/w | يحصل على نصف قطر Gausseian [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| سيغما | float | r/w | يحصل على سيغما نواة Gaussian (التنعيم). يجب أن تكون قيمة موجبة غير صفرية. |
| الحجم | int | r/w | يحصل على حجم نواة Gaussian. يجب أن تكون قيمة موجبة غير صفرية وفردية. |


### Constructor: GaussianBlurFilterOptions() {#GaussianBlurFilterOptions__1}


```
 GaussianBlurFilterOptions() 
```

ينشئ مثيلاً جديداً للفئة [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/).

### Constructor: GaussianBlurFilterOptions(size, sigma) {#GaussianBlurFilterOptions_size_sigma_2}


```
 GaussianBlurFilterOptions(size, sigma) 
```

ينشئ مثيلاً جديداً للفئة [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحجم | int | حجم نواة Gaussian.. |
| سيغما | float | سيغما نواة Gaussian. |

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
	# تطبيق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح تمهيد ثنائي الجانب بحجم نواة 5 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح غاوس-وينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح حركة وينر بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

