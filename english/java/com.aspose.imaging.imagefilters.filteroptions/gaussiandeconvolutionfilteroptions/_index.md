---
title: GaussianDeconvolutionFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: The deconvolution filter options using Gaussian blurring.
type: docs
weight: 20
url: /java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

The deconvolution filter options using Gaussian blurring.
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Gets the Gaussian kernel size. |
| [setSize(int value)](#setSize-int-) | The Gaussian kernel size. |
| [getSigma()](#getSigma--) | Gets the Gaussian kernel sigma (smoothing). |
| [setSigma(double value)](#setSigma-double-) | The Gaussian kernel sigma (smoothing). |
| [getRadius()](#getRadius--) | Gets the radius of Gausseian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | The radius of Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


Gets the Gaussian kernel size. Must be a positive non-zero odd value.

**Returns:**
int - the Gaussian kernel size.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


The Gaussian kernel size. Must be a positive non-zero odd value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the Gaussian kernel size. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Gets the Gaussian kernel sigma (smoothing). Must be a positive non-zero value.

**Returns:**
double - the Gaussian kernel sigma (smoothing).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


The Gaussian kernel sigma (smoothing). Must be a positive non-zero value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the Gaussian kernel sigma (smoothing). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Gets the radius of Gausseian ISquareConvolutionKernel.

**Returns:**
int - the radius of Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


The radius of Gausseian ISquareConvolutionKernel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the radius of Gausseian ISquareConvolutionKernel. |

