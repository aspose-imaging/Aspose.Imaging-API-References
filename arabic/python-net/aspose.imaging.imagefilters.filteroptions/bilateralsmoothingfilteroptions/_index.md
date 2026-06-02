---
title: "فئة BilateralSmoothingFilterOptions"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---

**Summary:** The Bilateral Smoothing Filter Options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions__1) | يقوم بإنشاء نسخة جديدة من الفئة [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/). |
| [BilateralSmoothingFilterOptions(size)](#BilateralSmoothingFilterOptions_size_2) | يقوم بإنشاء نسخة جديدة من الفئة [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| color_factor | float | r/w | يحصل أو يضبط معامل اللون. |
| color_power | float | r/w | يحصل أو يضبط قوة اللون. |
| الحجم | int | r/w | يحصل أو يضبط حجم النواة. |
| spatial_factor | float | r/w | يحصل أو يضبط معامل الفضاء. |
| spatial_power | float | r/w | يحصل أو يضبط قوة الفضاء. |


### Constructor: BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions__1}


```
 BilateralSmoothingFilterOptions() 
```

يقوم بإنشاء نسخة جديدة من الفئة [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/).

### Constructor: BilateralSmoothingFilterOptions(size) {#BilateralSmoothingFilterOptions_size_2}


```
 BilateralSmoothingFilterOptions(size) 
```

يقوم بإنشاء نسخة جديدة من الفئة [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحجم | int | حجم النواة. |

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

