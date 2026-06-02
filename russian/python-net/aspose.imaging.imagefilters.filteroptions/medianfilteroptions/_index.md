---
title: "Класс MedianFilterOptions"
type: docs
weight: 130
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---

**Summary:** Median filter

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MedianFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MedianFilterOptions(size)](#MedianFilterOptions_size_1) | Инициализирует новый экземпляр класса [MedianFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Получает или задает размер. |


### Constructor: MedianFilterOptions(size) {#MedianFilterOptions_size_1}


```
 MedianFilterOptions(size) 
```

Инициализирует новый экземпляр класса [MedianFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | int | Размер прямоугольника фильтра. |

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
	# Применить медианный фильтр с размером прямоугольника 5 к всему изображению.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Применить билатеральный сглаживающий фильтр с размером ядра 5 к всему изображению.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Применить гауссов размытие с радиусом 5 и значением сигмы 4.0 к всему изображению.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Применить фильтр Гаусса-Винера с радиусом 5 и значением сглаживания 4.0 к всему изображению.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Применить фильтр движения Винера с длиной 5, значением сглаживания 4.0 и углом 90.0 градусов к всему изображению.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Применить фильтр резкости с размером ядра 5 и значением сигмы 4.0 к всему изображению.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

