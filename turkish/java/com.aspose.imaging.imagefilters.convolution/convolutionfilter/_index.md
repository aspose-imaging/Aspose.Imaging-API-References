---
title: "ConvolutionFilter"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Çekirdek matris sağlayıcı sınıfı."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

Çekirdek matris sağlayıcı sınıfı.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | 3x3 keskinleştirme çekirdeğini alır. |
| [getSharpen5x5()](#getSharpen5x5--) | 5x5 keskinleştirme çekirdeğini alır. |
| [getEmboss3x3()](#getEmboss3x3--) | 3x3 kabartma çekirdeğini alır. |
| [getEmboss5x5()](#getEmboss5x5--) | 5x5 kabartma çekirdeğini alır. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Hareket bulanıklığı çekirdeğini alır. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Gauss çekirdeğini alır. |
| [getBlurBox(int size)](#getBlurBox-int-) | Kutu bulanıklığı çekirdeğini alır. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | `kernel`i bir [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) çekirdeğine dönüştürür. |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


3x3 keskinleştirme çekirdeğini alır.

**Returns:**
double[][] - 3x3 keskinleştirme çekirdeği.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


5x5 keskinleştirme çekirdeğini alır.

**Returns:**
double[][] - 5x5 keskinleştirme çekirdeği.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


3x3 kabartma çekirdeğini alır.

**Returns:**
double[][] - 3x3 kabartma çekirdeği.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


5x5 kabartma çekirdeğini alır.

**Returns:**
double[][] - 5x5 kabartma çekirdeği.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Hareket bulanıklığı çekirdeğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Çekirdek boyutu. |
| angle | double | Hareket açısı. |

**Returns:**
double[][] - Hareket bulanıklığı çekirdeği.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Gauss çekirdeğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Çekirdek boyutu. |
| sigma | double | Sigma değeri (0... ] aralığında). |

**Returns:**
double[][] - Gaussian çekirdeği.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Kutu bulanıklığı çekirdeğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Çekirdek boyutu. |

**Returns:**
double[][] - Kutu bulanıklaştırma çekirdeği.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


`kernel`i bir [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) çekirdeğine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çekirdek | double[][] | Çekirdek. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - Bir [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) çekirdek.
