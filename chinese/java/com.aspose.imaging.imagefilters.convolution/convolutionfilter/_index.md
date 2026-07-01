---
title: "ConvolutionFilter"
second_title: "Aspose.Imaging for Java API 参考"
description: "内核矩阵提供程序类。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

内核矩阵提供程序类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | 获取 3x3 锐化核。 |
| [getSharpen5x5()](#getSharpen5x5--) | 获取 5x5 锐化核。 |
| [getEmboss3x3()](#getEmboss3x3--) | 获取 3x3 浮雕核。 |
| [getEmboss5x5()](#getEmboss5x5--) | 获取 5x5 浮雕核。 |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | 获取运动模糊核。 |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | 获取高斯核。 |
| [getBlurBox(int size)](#getBlurBox-int-) | 获取盒式模糊核。 |
| [toComplex(double[][] kernel)](#toComplex-double-----) | 将 `kernel` 转换为 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 核。 |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


获取 3x3 锐化核。

**Returns:**
double[][] - 3x3 锐化核。
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


获取 5x5 锐化核。

**Returns:**
double[][] - 5x5 锐化核。
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


获取 3x3 浮雕核。

**Returns:**
double[][] - 3x3 浮雕核。
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


获取 5x5 浮雕核。

**Returns:**
double[][] - 5x5 浮雕核。
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


获取运动模糊核。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | int | 内核大小。 |
| angle | double | 运动角度。 |

**Returns:**
double[][] - 运动模糊核。
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


获取高斯核。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | int | 内核大小。 |
| sigma | double | sigma 值的范围为 (0...]. |

**Returns:**
double[][] - 高斯核。
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


获取盒式模糊核。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | int | 内核大小。 |

**Returns:**
double[][] - 方框模糊核。
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


将 `kernel` 转换为 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 核。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 核 | double[][] | 内核。 |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - 一个 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 核。
