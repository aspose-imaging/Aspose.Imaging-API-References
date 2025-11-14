---
title: GaussianDeconvolutionFilterOptions Class
type: docs
weight: 110
url: /python-net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---

**Summary:** The deconvolution filter options using Gaussian bluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions

**Inheritance:** DeconvolutionFilterOptions

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brightness | float | r/w | Gets or sets the brightness.<br/>            recommended range 1 - 1.5<br/>            default value = 1.15 |
| grayscale | bool | r/w | Gets or sets a value indicating whether this [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) is grayscale.<br/>            Return grayscale mode or RGB mode. |
| is_partial_loaded | bool | r | Gets a value indicating whether this instance is partial loaded. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Gets the kernel. |
| radius | int | r/w | Gets the radius of Gausseian [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| sigma | float | r/w | Gets the Gaussian kernel sigma (smoothing). Must be a positive non-zero value. |
| size | int | r/w | Gets the Gaussian kernel size. Must be a positive non-zero odd value. |
| snr | float | r/w | Gets or sets the SNR(signal-to-noise ratio)<br/>            recommended range 0.002 - 0.009, default value = 0.007 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Initializes a new instance of the [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) class. |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Initializes a new instance of the [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) class. |


### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Initializes a new instance of the [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The Complex[] kernel. |

**Returns**

| Type | Description |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Initializes a new instance of the [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| kernel | float[] | The double[] kernel. |

**Returns**

| Type | Description |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


