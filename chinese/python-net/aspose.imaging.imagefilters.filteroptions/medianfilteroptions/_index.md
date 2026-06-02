---
title: "MedianFilterOptions 类"
type: docs
weight: 130
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---

**Summary:** Median filter

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MedianFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [MedianFilterOptions(size)](#MedianFilterOptions_size_1) | 初始化 [MedianFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| size | int | r/w | 获取或设置大小。 |


### Constructor: MedianFilterOptions(size) {#MedianFilterOptions_size_1}


```
 MedianFilterOptions(size) 
```

初始化 [MedianFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | int | 过滤矩形的大小。 |

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
	# 对整幅图像应用矩形大小为 5 的中值滤波器。
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用核大小为 5 的双边平滑滤波器。
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用半径为 5、sigma 值为 4.0 的高斯模糊滤波器。
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用核大小为 5、sigma 值为 4.0 的锐化滤波器。
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

