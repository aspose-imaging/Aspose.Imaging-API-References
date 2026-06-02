---
title: "فئة MotionWienerFilterOptions"
type: docs
weight: 140
url: /ar/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** The motion debluring filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [MotionWienerFilterOptions(size, sigma, angle)](#MotionWienerFilterOptions_size_sigma_angle_1) | ينشئ مثيلاً جديداً من الفئة [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| angle | float | r/w | يحصل أو يضبط الزاوية بالدرجات. |
| السطوع | float | r/w | يحصل أو يضبط السطوع.<br/>            النطاق الموصى به 1 - 1.5<br/>            القيمة الافتراضية = 1.15 |
| grayscale | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) في وضع التدرج الرمادي.<br/>            إرجاع وضع التدرج الرمادي أو وضع RGB. |
| is_partial_loaded | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | يحصل على النواة. |
| radius | int | r/w | يحصل على نصف قطر Gausseian [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| سيغما | float | r/w | يحصل على سيغما نواة Gaussian (التنعيم). يجب أن تكون قيمة موجبة غير صفرية. |
| الحجم | int | r/w | يحصل على حجم نواة Gaussian. يجب أن تكون قيمة موجبة غير صفرية وفردية. |
| snr | float | r/w | يحصل أو يضبط SNR (نسبة الإشارة إلى الضوضاء)<br/>            النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Constructor: MotionWienerFilterOptions(size, sigma, angle) {#MotionWienerFilterOptions_size_sigma_angle_1}


```
 MotionWienerFilterOptions(size, sigma, angle) 
```

ينشئ مثيلاً جديداً من الفئة [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحجم | int | حجم نواة Gaussian. |
| سيغما | float | سيغما نواة Gaussian. |
| angle | float | الزاوية بالدرجات. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | نواة Complex[] . |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| نواة | float[] | نواة double[] . |

**Returns**

| نوع | الوصف |
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

