---
title: "ConvolutionFilterOptions 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | 使用 factor = 1 且 bias = 0 初始化 [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) 类的新实例。 |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | 使用 bias = 0 初始化 [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) 类的新实例。 |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | 初始化 [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 偏置 | int | r/w | 获取或设置偏置。 |
| borders_processing | bool | r/w | 获取或设置一个值，指示是否进行 [borders processing]。 |
| 因子 | float | r/w | 获取或设置因子。 |
| ignore_alpha | bool | r/w | 获取或设置一个值，指示是否 [ignore alpha]。 |
| kernel_data | float[] | r | 获取核。 |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

使用 factor = 1 且 bias = 0 初始化 [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 核 | float[] | X 轴方向的卷积核。 |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

使用 bias = 0 初始化 [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 核 | float[] | X 轴方向的卷积核。 |
| 因子 | float | 因子。 |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

初始化 [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 核 | float[] | X 轴方向的卷积核。 |
| 因子 | float | 因子。 |
| 偏置 | int | 偏置值。 |

