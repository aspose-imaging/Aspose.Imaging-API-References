---
title: ConvolutionFilterOptions Class
type: docs
weight: 60
url: /python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | Initializes a new instance of the [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) class with factor = 1, and bias = 0. |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | Initializes a new instance of the [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) class with bias = 0. |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | Initializes a new instance of the [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Gets or sets the bias. |
| borders_processing | bool | r/w | Gets or sets a value indicating whether [borders processing]. |
| factor | float | r/w | Gets or sets the factor. |
| ignore_alpha | bool | r/w | Gets or sets a value indicating whether [ignore alpha]. |
| kernel_data | float[] | r | Gets the kernel. |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

Initializes a new instance of the [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) class with factor = 1, and bias = 0.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| kernel | float[] | The convolution kernel for X-axis direction. |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

Initializes a new instance of the [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) class with bias = 0.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| kernel | float[] | The convolution kernel for X-axis direction. |
| factor | float | The factor. |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

Initializes a new instance of the [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| kernel | float[] | The convolution kernel for X-axis direction. |
| factor | float | The factor. |
| bias | int | The bias value. |

