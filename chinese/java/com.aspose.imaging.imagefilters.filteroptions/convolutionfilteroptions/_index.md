---
title: "ConvolutionFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "卷积滤镜选项。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

卷积滤镜选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | 初始化 [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) 类的新实例，factor == 1 且 bias == 0。 |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | 初始化 [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) 类的新实例，bias == 0。 |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | 初始化 [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getKernel()](#getKernel--) | 获取核。 |
| [getFactor()](#getFactor--) | 获取因子。 |
| [setFactor(double value)](#setFactor-double-) | 设置因子。 |
| [getBias()](#getBias--) | 获取偏置。 |
| [setBias(int value)](#setBias-int-) | 设置偏置。 |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | 获取指示是否[ignore alpha]的值。 |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | 设置指示是否[ignore alpha]的值。 |
| [getBordersProcessing()](#getBordersProcessing--) | 获取指示是否[borders processing]的值。 |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | 设置指示是否[borders processing]的值。 |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


初始化 [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) 类的新实例，factor == 1 且 bias == 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 核 | double[][] | X 轴方向的卷积核。 |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


初始化 [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) 类的新实例，bias == 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 核 | double[][] | X 轴方向的卷积核。 |
| 因子 | double | 因子。 |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


初始化 [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 核 | double[][] | X 轴方向的卷积核。 |
| 因子 | double | 因子。 |
| 偏置 | int | 偏置值。 |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


获取核。

**Returns:**
double[][] - 核。
### getFactor() {#getFactor--}
```
public final double getFactor()
```


获取因子。

**Returns:**
double - 因子。
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


设置因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 因子。 |

### getBias() {#getBias--}
```
public final int getBias()
```


获取偏置。

值：偏置。

**Returns:**
int - 偏置。
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


设置偏置。

值：偏置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 偏置。 |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


获取指示是否[ignore alpha]的值。

值：`true` 表示[ignore alpha]；否则为 `false`。

**Returns:**
boolean - 表示是否[ignore alpha]的值。
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


设置指示是否[ignore alpha]的值。

值：`true` 表示[ignore alpha]；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 表示是否[ignore alpha]的值。 |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


获取指示是否[borders processing]的值。

值：`true` 表示[borders processing]；否则为 `false`。

**Returns:**
boolean - 一个指示是否进行[borders processing]的值。
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


设置指示是否[borders processing]的值。

值：`true` 表示[borders processing]；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 一个指示是否进行[borders processing]的值。 |

