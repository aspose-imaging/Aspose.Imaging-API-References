---
title: "SharpenFilterOptions Класс"
type: docs
weight: 160
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---

**Summary:** The sharpen filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions

**Inheritance:** GaussianBlurFilterOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SharpenFilterOptions()](#SharpenFilterOptions__1) | Инициализирует новый экземпляр класса [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) |
| [SharpenFilterOptions(size, sigma)](#SharpenFilterOptions_size_sigma_2) | Инициализирует новый экземпляр класса [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Получает или задает bias. |
| borders_processing | bool | r/w | Получает или задает значение, указывающее, включена ли [borders processing]. |
| factor | float | r/w | Получает или задает factor. |
| ignore_alpha | bool | r/w | Получает или задает значение, указывающее, включено ли [ignore alpha]. |
| kernel_data | float[] | r | Получает ядро. |
| radius | int | r/w | Получает радиус гауссовского [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| сигма | float | r/w | Получает сигму гауссовского ядра (сглаживание). Должно быть положительным ненулевым значением. |
| size | int | r/w | Получает размер гауссовского ядра. Должно быть положительным ненулевым нечетным значением. |


### Constructor: SharpenFilterOptions() {#SharpenFilterOptions__1}


```
 SharpenFilterOptions() 
```

Инициализирует новый экземпляр класса [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/)

### Constructor: SharpenFilterOptions(size, sigma) {#SharpenFilterOptions_size_sigma_2}


```
 SharpenFilterOptions(size, sigma) 
```

Инициализирует новый экземпляр класса [SharpenFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | int | Размер ядра. |
| сигма | float | Сигма. |

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

