---
title: "GaussianDeconvolutionFilterOptions 类"
type: docs
weight: 110
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---

**Summary:** The deconvolution filter options using Gaussian bluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions

**Inheritance:** DeconvolutionFilterOptions

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


