---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "提供用于配置 Auto White Balance 滤镜的选项。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

提供 Auto White Balance 滤镜的配置选项。允许调节对比度拉伸参数和通道缩放，以改善数字图像的外观。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | 初始化 [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | 获取对比度拉伸的目标高百分位。 |
| [getTargetValue()](#getTargetValue--) | 获取高百分位的目标值。 |
| [getMaxScale()](#getMaxScale--) | 获取每个通道的最大缩放因子。 |
| [getLowPercentile()](#getLowPercentile--) | 低百分位用于黑点，作为暗部保护使用（默认值：3）。 |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | 低百分位以下的偏移量，暗像素不被拉伸（保护）。 |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


初始化 [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lowPercentile | int | 低百分位用于黑点，作为暗部保护使用（默认值：3）。 |
| targetHighPercentile | int | 对比度拉伸的目标高百分位（默认值 97）。 |
| targetValue | int | 高百分位的目标值（默认值 255）。 |
| maxScale | float | 每个通道的最大缩放因子（默认值 1.4f）。 |
| protectedDarkOffset | int | 低百分位以下的偏移量，暗像素不被拉伸（保护）。 |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


获取对比度拉伸的目标高百分位。确定哪个亮度百分位将映射到目标值。

**Returns:**
int - 对比度拉伸的目标高百分位。
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


获取高百分位的目标值。该值将用作对比度拉伸的白色参考。

**Returns:**
int - 高百分位的目标值。
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


获取每个通道的最大缩放因子。限制任何通道的放大，以避免过度的颜色偏移。

**Returns:**
float - 每个通道的最大缩放因子。
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


低百分位用于黑点，作为暗部保护使用（默认值：3）。

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


低百分位以下的偏移量，暗像素不被拉伸（保护）。

**Returns:**
int
