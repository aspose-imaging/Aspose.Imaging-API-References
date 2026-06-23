---
title: "DeconvolutionFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "Deconvolution Filter Options 抽象类"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

去卷积滤镜选项，抽象类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | 初始化 [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) 类的新实例。 |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | 初始化 [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getKernel()](#getKernel--) | 获取核。 |
| [getSnr()](#getSnr--) | 获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007 |
| [setSnr(double value)](#setSnr-double-) | 获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007 |
| [getBrightness()](#getBrightness--) | 获取或设置亮度。 |
| [setBrightness(double value)](#setBrightness-double-) | 获取或设置亮度。 |
| [getGrayscale()](#getGrayscale--) | 获取或设置一个值，指示此 `DeconvolutionFilterOptions` 是否为灰度。 |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | 获取或设置一个值，指示此 `DeconvolutionFilterOptions` 是否为灰度。 |
| [isPartialLoaded()](#isPartialLoaded--) | 获取一个值，指示此实例是否已部分加载。 |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


初始化 [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 核 | double[][] | 内核。 |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


初始化 [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 内核。 |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


获取核。

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - 核。
### getSnr() {#getSnr--}
```
public double getSnr()
```


获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007

值：SNR。

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007

值：SNR。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


获取或设置亮度。推荐范围 1 - 1.5，默认值 = 1.15

值：亮度。

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


获取或设置亮度。推荐范围 1 - 1.5，默认值 = 1.15

值：亮度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


获取或设置一个值，指示此 `DeconvolutionFilterOptions` 是否为灰度。返回灰度模式或 RGB 模式。

值：如果为灰度则为 `true`；否则为 `false`。

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


获取或设置一个值，指示此 `DeconvolutionFilterOptions` 是否为灰度。返回灰度模式或 RGB 模式。

值：如果为灰度则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


获取一个值，指示此实例是否已部分加载。

值：如果此实例已部分加载则为 `true`；否则为 `false`。

**Returns:**
boolean
