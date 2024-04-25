---
title: ConvolutionFilter
second_title: Aspose.Imaging for Java API Reference
description: The kernel matrix provider class.
type: docs
weight: 10
url: /com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

The kernel matrix provider class.
## Methods

| Method | Description |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | Gets the 3x3 sharpen kernel. |
| [getSharpen5x5()](#getSharpen5x5--) | Gets the 5x5 sharpen kernel. |
| [getEmboss3x3()](#getEmboss3x3--) | Gets the 3x3 Emboss kernel. |
| [getEmboss5x5()](#getEmboss5x5--) | Gets the 5x5 Emboss kernel. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Gets the motion blur kernel. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Gets the Gaussian kernel. |
| [getBlurBox(int size)](#getBlurBox-int-) | Gets the box blur kernel. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | Converts `kernel` to a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) kernel. |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


Gets the 3x3 sharpen kernel.

**Returns:**
double[][] - the 3x3 sharpen kernel.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


Gets the 5x5 sharpen kernel.

**Returns:**
double[][] - the 5x5 sharpen kernel.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


Gets the 3x3 Emboss kernel.

**Returns:**
double[][] - the 3x3 Emboss kernel.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


Gets the 5x5 Emboss kernel.

**Returns:**
double[][] - the 5x5 Emboss kernel.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Gets the motion blur kernel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The kernel size. |
| angle | double | The motion angle. |

**Returns:**
double[][] - The motion blur kernel.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Gets the Gaussian kernel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The kernel size. |
| sigma | double | The sigma value in range (0...]. |

**Returns:**
double[][] - The Gaussian kernel.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Gets the box blur kernel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The kernel size. |

**Returns:**
double[][] - The box blur kernel.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


Converts `kernel` to a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) kernel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kernel | double[][] | The kernel. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - A [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) kernel.
