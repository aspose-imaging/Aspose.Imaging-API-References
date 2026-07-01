---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用高斯模糊的去卷积滤镜选项。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

使用高斯模糊的去卷积滤镜选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 获取 Gaussian 核的大小。 |
| [setSize(int value)](#setSize-int-) | 高斯核的大小。 |
| [getSigma()](#getSigma--) | 获取 Gaussian 核 sigma（平滑）。 |
| [setSigma(double value)](#setSigma-double-) | Gaussian 核 sigma（平滑）。 |
| [getRadius()](#getRadius--) | 获取 Gausseian ISquareConvolutionKernel 的半径。 |
| [setRadius(int value)](#setRadius-int-) | Gausseian ISquareConvolutionKernel 的半径。 |
### getSize() {#getSize--}
```
public final int getSize()
```


获取 Gaussian 核大小。必须是正的、非零的奇数值。

**Returns:**
int - Gaussian 核大小。
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Gaussian 核大小。必须是正的、非零的奇数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | Gaussian 核大小。 |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


获取 Gaussian 核 sigma（平滑）。必须是正的、非零的值。

**Returns:**
double - Gaussian 核 sigma（平滑）。
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


Gaussian 核 sigma（平滑）。必须是正的、非零的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | Gaussian 核 sigma（平滑）。 |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


获取 Gausseian ISquareConvolutionKernel 的半径。

**Returns:**
int - Gausseian ISquareConvolutionKernel 的半径。
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Gausseian ISquareConvolutionKernel 的半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | Gausseian ISquareConvolutionKernel 的半径。 |

