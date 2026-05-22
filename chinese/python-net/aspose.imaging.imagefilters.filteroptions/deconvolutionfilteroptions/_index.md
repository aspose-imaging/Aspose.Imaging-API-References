---
title: "DeconvolutionFilterOptions 类"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---

**Summary:** Deconvolution Filter Options, abstract class

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_1) | 初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。 |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_2) | 初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 亮度 | float | r/w | 获取或设置亮度。<br/>            推荐范围 1 - 1.5<br/>            默认值 = 1.15 |
| grayscale | bool | r/w | 获取或设置一个值，以指示此 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 是否为灰度。<br/>            返回灰度模式或 RGB 模式。 |
| is_partial_loaded | bool | r | 获取一个值，指示此实例是否部分加载。 |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | 获取核。 |
| snr | float | r/w | 获取或设置 SNR（信噪比）<br/>            推荐范围 0.002 - 0.009，默认值 = 0.007 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | 初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。 |
| [create_with_double(kernel)](#create_with_double_kernel_2) | 初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。 |


### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_1}


```
 DeconvolutionFilterOptions(kernel) 
```

初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 核 | float[] | 该核。 |

### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_2}


```
 DeconvolutionFilterOptions(kernel) 
```

初始化一个新的 [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该核。 |

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


