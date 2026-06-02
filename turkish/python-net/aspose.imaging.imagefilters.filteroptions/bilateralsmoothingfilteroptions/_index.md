---
title: "BilateralSmoothingFilterOptions Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---

**Summary:** The Bilateral Smoothing Filter Options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions__1) | [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) sınıfının yeni bir örneğini başlatır. |
| [BilateralSmoothingFilterOptions(size)](#BilateralSmoothingFilterOptions_size_2) | [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| color_factor | float | r/w | Renk faktörünü alır veya ayarlar. |
| color_power | float | r/w | Renk gücünü alır veya ayarlar. |
| size | int | r/w | Çekirdeğin boyutunu alır veya ayarlar. |
| spatial_factor | float | r/w | Uzamsal faktörü alır veya ayarlar. |
| spatial_power | float | r/w | Uzamsal gücü alır veya ayarlar. |


### Constructor: BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions__1}


```
 BilateralSmoothingFilterOptions() 
```

[BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) sınıfının yeni bir örneğini başlatır.

### Constructor: BilateralSmoothingFilterOptions(size) {#BilateralSmoothingFilterOptions_size_2}


```
 BilateralSmoothingFilterOptions(size) 
```

[BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | int | Kernalın boyutu. |

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

