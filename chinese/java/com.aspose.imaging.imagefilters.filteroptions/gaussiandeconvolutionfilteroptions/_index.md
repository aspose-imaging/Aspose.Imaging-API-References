---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
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
| [getSize()](#getSize--) | 获取高斯内核大小。 |
| [setSize(int value)](#setSize-int-) | 高斯核的大小。 |
| [getSigma()](#getSigma--) | 获取高斯内核 sigma（平滑）。 |
| [setSigma(double value)](#setSigma-double-) | 高斯核 sigma（平滑）。 |
| [getRadius()](#getRadius--) | 获取 Gausseian ISquareConvolutionKernel 的半径。 |
| [setRadius(int value)](#setRadius-int-) | Gausseian ISquareConvolutionKernel 的半径。 |
### getSize() {#getSize--}
```
public final int getSize()
```


获取高斯核大小。必须是正的非零奇数值。

**Returns:**
int - 高斯核大小。
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


高斯核大小。必须是正的非零奇数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 高斯核大小。 |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


获取高斯核 sigma（平滑）。必须是正的非零值。

**Returns:**
double - 高斯核 sigma（平滑）。
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


高斯核 sigma（平滑）。必须是正的非零值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 高斯核 sigma（平滑）。 |

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
| value | int | Gausseian ISquareConvolutionKernel 的半径。 |

