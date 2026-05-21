---
title: "ConvolutionFilter"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den kernel matrix provider class."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

Den kernel matrix provider class.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | Hämtar 3x3 skärpningskärnan. |
| [getSharpen5x5()](#getSharpen5x5--) | Hämtar 5x5 skärpningskärnan. |
| [getEmboss3x3()](#getEmboss3x3--) | Hämtar 3x3 reliefkärnan. |
| [getEmboss5x5()](#getEmboss5x5--) | Hämtar 5x5 reliefkärnan. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Hämtar rörelseoskärningskärnan. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Hämtar den Gaussiska kärnan. |
| [getBlurBox(int size)](#getBlurBox-int-) | Hämtar boxblur-kärnan. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | Konverterar `kernel` till en [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) kärna. |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


Hämtar 3x3 skärpningskärnan.

**Returns:**
double[][] - den 3x3 skärpningskärnan.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


Hämtar 5x5 skärpningskärnan.

**Returns:**
double[][] - den 5x5 skärpningskärnan.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


Hämtar 3x3 reliefkärnan.

**Returns:**
double[][] - den 3x3 reliefkärnan.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


Hämtar 5x5 reliefkärnan.

**Returns:**
double[][] - den 5x5 reliefkärnan.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Hämtar rörelseoskärningskärnan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Kärnans storlek. |
| angle | double | Rörelsevinkeln. |

**Returns:**
double[][] - den rörelseoskärningskärnan.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Hämtar den Gaussiska kärnan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Kärnans storlek. |
| sigma | double | Sigma-värdet i intervallet (0...]. |

**Returns:**
double[][] - Den gaussiska kärnan.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Hämtar boxblur-kärnan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Kärnans storlek. |

**Returns:**
double[][] - Boxblur-kärnan.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


Konverterar `kernel` till en [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) kärna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kärna | double[][] | Kärnan. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - En [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) kärna.
