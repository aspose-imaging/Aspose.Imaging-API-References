---
title: "JpegLsPresetCodingParameters"
second_title: "Aspose.Imaging for Java API 参考"
description: "定义 JPEG-LS 预设编码参数，定义于 ISO/IEC 14495-1 C.2.4.1.1。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/
---
**Inheritance:**
java.lang.Object
```
public class JpegLsPresetCodingParameters
```

定义 JPEG-LS 预设编码参数，定义于 ISO/IEC 14495-1, C.2.4.1.1。JPEG-LS 定义了一套默认参数，但可以使用自定义参数。使用时，这些参数会写入编码位流，以满足解码过程的需要。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpegLsPresetCodingParameters()](#JpegLsPresetCodingParameters--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMaximumSampleValue()](#getMaximumSampleValue--) | 获取或设置扫描中任何图像样本的最大可能值。 |
| [setMaximumSampleValue(int value)](#setMaximumSampleValue-int-) | 获取或设置扫描中任何图像样本的最大可能值。 |
| [getThreshold1()](#getThreshold1--) | 获取或设置局部梯度的第一个量化阈值。 |
| [setThreshold1(int value)](#setThreshold1-int-) | 获取或设置局部梯度的第一个量化阈值。 |
| [getThreshold2()](#getThreshold2--) | 获取或设置局部梯度的第二个量化阈值。 |
| [setThreshold2(int value)](#setThreshold2-int-) | 获取或设置局部梯度的第二个量化阈值。 |
| [getThreshold3()](#getThreshold3--) | 获取或设置局部梯度的第三个量化阈值。 |
| [setThreshold3(int value)](#setThreshold3-int-) | 获取或设置局部梯度的第三个量化阈值。 |
| [getResetValue()](#getResetValue--) | 获取或设置计数器 A、B 和 N 被减半的阈值。 |
| [setResetValue(int value)](#setResetValue-int-) | 获取或设置计数器 A、B 和 N 被减半的阈值。 |
### JpegLsPresetCodingParameters() {#JpegLsPresetCodingParameters--}
```
public JpegLsPresetCodingParameters()
```


### getMaximumSampleValue() {#getMaximumSampleValue--}
```
public int getMaximumSampleValue()
```


获取或设置扫描中任何图像样本的最大可能值。该值必须大于或等于扫描中各组件的实际最大值。

**Returns:**
int
### setMaximumSampleValue(int value) {#setMaximumSampleValue-int-}
```
public void setMaximumSampleValue(int value)
```


获取或设置扫描中任何图像样本的最大可能值。该值必须大于或等于扫描中各组件的实际最大值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getThreshold1() {#getThreshold1--}
```
public int getThreshold1()
```


获取或设置局部梯度的第一个量化阈值。

**Returns:**
int
### setThreshold1(int value) {#setThreshold1-int-}
```
public void setThreshold1(int value)
```


获取或设置局部梯度的第一个量化阈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getThreshold2() {#getThreshold2--}
```
public int getThreshold2()
```


获取或设置局部梯度的第二个量化阈值。

**Returns:**
int
### setThreshold2(int value) {#setThreshold2-int-}
```
public void setThreshold2(int value)
```


获取或设置局部梯度的第二个量化阈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getThreshold3() {#getThreshold3--}
```
public int getThreshold3()
```


获取或设置局部梯度的第三个量化阈值。

**Returns:**
int
### setThreshold3(int value) {#setThreshold3-int-}
```
public void setThreshold3(int value)
```


获取或设置局部梯度的第三个量化阈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getResetValue() {#getResetValue--}
```
public int getResetValue()
```


获取或设置计数器 A、B 和 N 被减半的阈值。

**Returns:**
int
### setResetValue(int value) {#setResetValue-int-}
```
public void setResetValue(int value)
```


获取或设置计数器 A、B 和 N 被减半的阈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

