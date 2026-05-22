---
title: "GaussWienerFilterOptions 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener filter options for image debluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | 初始化 [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) 类的新实例。 |
| [GaussWienerFilterOptions(size, sigma)](#GaussWienerFilterOptions_size_sigma_2) | 初始化 [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 亮度 | float | r/w | 获取或设置亮度。<br/>            推荐范围 1 - 1.5<br/>            默认值 = 1.15 |
| grayscale | bool | r/w | 获取或设置一个值，以指示此 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 是否为灰度。<br/>            返回灰度模式或 RGB 模式。 |
| is_partial_loaded | bool | r | 获取一个值，指示此实例是否部分加载。 |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | 获取核。 |
| radius | int | r/w | 获取高斯 [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/) 的半径。 |
| sigma | float | r/w | 获取高斯核 sigma（平滑）。必须为正的非零值。 |
| size | int | r/w | 获取高斯核大小。必须为正的非零奇数值。 |
| snr | float | r/w | 获取或设置 SNR（信噪比）<br/>            推荐范围 0.002 - 0.009，默认值 = 0.007 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | 初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。 |
| [create_with_double(kernel)](#create_with_double_kernel_2) | 初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

初始化 [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) 类的新实例。

### Constructor: GaussWienerFilterOptions(size, sigma) {#GaussWienerFilterOptions_size_sigma_2}


```
 GaussWienerFilterOptions(size, sigma) 
```

初始化 [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | int | 高斯核大小。 |
| sigma | float | 高斯核 sigma。 |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Complex[] 核。 |

**Returns**

| Type | Description |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 核 | float[] | double[] 核。 |

**Returns**

| Type | Description |
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

