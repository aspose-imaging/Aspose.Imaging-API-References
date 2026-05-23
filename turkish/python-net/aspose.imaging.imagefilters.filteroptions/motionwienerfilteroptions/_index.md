---
title: "MotionWienerFilterOptions Sınıfı"
type: docs
weight: 140
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** The motion debluring filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [MotionWienerFilterOptions(size, sigma, angle)](#MotionWienerFilterOptions_size_sigma_angle_1) | Yeni bir [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| angle | float | r/w | Açıyı derece cinsinden alır veya ayarlar. |
| parlaklık | float | r/w | Parlaklığı alır veya ayarlar.<br/>            önerilen aralık 1 - 1.5<br/>            varsayılan değer = 1.15 |
| grayscale | bool | r/w | Bu [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) nesnesinin gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Gri tonlamalı mod veya RGB modunu döndürür. |
| is_partial_loaded | bool | r | Bu örneğin kısmen yüklendiğini gösteren bir değeri alır. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Çekirdeği alır. |
| radius | int | r/w | Gaussian [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/) yarıçapını alır. |
| sigma | float | r/w | Gaussian çekirdek sigma değerini (yumuşatma) alır. Pozitif sıfır olmayan bir değer olmalıdır. |
| size | int | r/w | Gaussian çekirdek boyutunu alır. Pozitif sıfır olmayan tek bir değer olmalıdır. |
| snr | float | r/w | SNR (signal-to-noise ratio) değerini alır veya ayarlar.<br/>            önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007 |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır. |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır. |


### Constructor: MotionWienerFilterOptions(size, sigma, angle) {#MotionWienerFilterOptions_size_sigma_angle_1}


```
 MotionWienerFilterOptions(size, sigma, angle) 
```

Yeni bir [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | int | Gaussian çekirdek boyutu. |
| sigma | float | Gaussian çekirdek sigma. |
| angle | float | Açı derece cinsinden. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Complex[] çekirdeği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Yeni bir [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| çekirdek | float[] | double[] çekirdeği. |

**Returns**

| Tür | Açıklama |
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

