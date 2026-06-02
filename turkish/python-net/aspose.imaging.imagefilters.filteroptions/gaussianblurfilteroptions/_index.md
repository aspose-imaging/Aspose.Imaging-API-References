---
title: "GaussianBlurFilterOptions Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---

**Summary:** The Gaussian blur filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions

**Inheritance:** ConvolutionFilterOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions__1) | Yeni bir [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/) sınıfının bir örneğini başlatır. |
| [GaussianBlurFilterOptions(size, sigma)](#GaussianBlurFilterOptions_size_sigma_2) | Yeni bir [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bias | int | r/w | bias değerini alır veya ayarlar. |
| borders_processing | bool | r/w | [borders processing] gösteren bir değeri alır veya ayarlar. |
| factor | float | r/w | factor değerini alır veya ayarlar. |
| ignore_alpha | bool | r/w | [ignore alpha] gösteren bir değeri alır veya ayarlar. |
| kernel_data | float[] | r | Gaussian çekirdeğini alır. |
| radius | int | r/w | Gaussian [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/) yarıçapını alır. |
| sigma | float | r/w | Gaussian çekirdek sigma değerini (yumuşatma) alır. Pozitif sıfır olmayan bir değer olmalıdır. |
| size | int | r/w | Gaussian çekirdek boyutunu alır. Pozitif sıfır olmayan tek bir değer olmalıdır. |


### Constructor: GaussianBlurFilterOptions() {#GaussianBlurFilterOptions__1}


```
 GaussianBlurFilterOptions() 
```

Yeni bir [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/) sınıfının bir örneğini başlatır.

### Constructor: GaussianBlurFilterOptions(size, sigma) {#GaussianBlurFilterOptions_size_sigma_2}


```
 GaussianBlurFilterOptions(size, sigma) 
```

Yeni bir [GaussianBlurFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | int | Gaussian çekirdek boyutu.. |
| sigma | float | Gaussian çekirdek sigma. |

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
	# Tüm görüntüye dikdörtgen boyutu 5 olan bir medyan filtresi uygulayın.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Tüm görüntüye çekirdek boyutu 5 olan bir ikili yumuşatma filtresi uygulayın.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Tüm görüntüye yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygulayın.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Tüm görüntüye yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygulayın.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Tüm görüntüye uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygulayın.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Tüm görüntüye çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygulayın.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

