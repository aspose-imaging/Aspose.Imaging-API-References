---
title: ConvolutionFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: The convolution filter options.
type: docs
weight: 12
url: /com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

The convolution filter options.
## Constructors

| Constructor | Description |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | Initializes a new instance of the [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) class with factor == 1 and bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | Initializes a new instance of the [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) class with bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Initializes a new instance of the [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getKernel()](#getKernel--) | Gets the kernel. |
| [getFactor()](#getFactor--) | Gets the factor. |
| [setFactor(double value)](#setFactor-double-) | Sets the factor. |
| [getBias()](#getBias--) | Gets the bias. |
| [setBias(int value)](#setBias-int-) | Sets the bias. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


Initializes a new instance of the [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) class with factor == 1 and bias == 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kernel | double[][] | The convolution kernel for X-axis direction. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


Initializes a new instance of the [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) class with bias == 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kernel | double[][] | The convolution kernel for X-axis direction. |
| factor | double | The factor. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Initializes a new instance of the [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kernel | double[][] | The convolution kernel for X-axis direction. |
| factor | double | The factor. |
| bias | int | The bias value. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Gets the kernel.

**Returns:**
double[][] - the kernel.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Gets the factor.

**Returns:**
double - the factor.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Sets the factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the factor. |

### getBias() {#getBias--}
```
public final int getBias()
```


Gets the bias.

Value: The bias.

**Returns:**
int - the bias.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


Sets the bias.

Value: The bias.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the bias. |

