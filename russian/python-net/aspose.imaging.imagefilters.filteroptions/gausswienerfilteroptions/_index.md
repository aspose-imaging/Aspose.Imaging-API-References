---
title: "Класс GaussWienerFilterOptions"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener filter options for image debluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Создает новый экземпляр класса [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/). |
| [GaussWienerFilterOptions(size, sigma)](#GaussWienerFilterOptions_size_sigma_2) | Создает новый экземпляр класса [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| яркость | float | r/w | Получает или задает яркость.<br/>            рекомендуемый диапазон 1 - 1.5<br/>            значение по умолчанию = 1.15 |
| grayscale | bool | r/w | Получает или задает значение, указывающее, является ли этот [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) градациями серого.<br/>            Возвращает режим градаций серого или режим RGB. |
| is_partial_loaded | bool | r | Получает значение, указывающее, частично ли загружен этот экземпляр. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Получает ядро. |
| radius | int | r/w | Получает радиус гауссовского [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| сигма | float | r/w | Получает сигму гауссовского ядра (сглаживание). Должно быть положительным ненулевым значением. |
| size | int | r/w | Получает размер гауссовского ядра. Должно быть положительным ненулевым нечетным значением. |
| snr | float | r/w | Получает или задает SNR (отношение сигнал/шум)<br/>            рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Создает новый экземпляр класса [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/).

### Constructor: GaussWienerFilterOptions(size, sigma) {#GaussWienerFilterOptions_size_sigma_2}


```
 GaussWienerFilterOptions(size, sigma) 
```

Создает новый экземпляр класса [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | int | Размер гауссовского ядра. |
| сигма | float | Сигма гауссовского ядра. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Ядро Complex[]. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ядро | float[] | Ядро double[]. |

**Returns**

| Тип | Описание |
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

