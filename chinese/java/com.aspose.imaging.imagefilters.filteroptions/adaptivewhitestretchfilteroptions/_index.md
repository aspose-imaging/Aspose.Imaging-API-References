---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "提供用于配置 Adaptive White Stretch 滤镜的选项。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

提供配置 Adaptive White Stretch 滤镜的选项。允许自定义直方图拉伸参数，以提升白色水平并改善淡文本或低对比度文档图像的可读性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | 初始化 AdaptiveWhiteStretchFilter 类的新实例。 |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | 初始化 AdaptiveWhiteStretchFilter 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | 获取一个值，指示过滤器是否在灰度模式下运行。 |
| [getLowPercentile()](#getLowPercentile--) | 获取用于计算黑点的下百分位。 |
| [getHighPercentile()](#getHighPercentile--) | 获取用于计算白点的上百分位。 |
| [getTargetWhite()](#getTargetWhite--) | 获取拉伸目标的目标白色值。 |
| [getMaxScale()](#getMaxScale--) | 获取允许的最大亮度比例。 |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


初始化 AdaptiveWhiteStretchFilter 类的新实例。

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


初始化 AdaptiveWhiteStretchFilter 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isGrayscale | boolean | 指示过滤器是否应在灰度模式下运行。 |
| lowPercentile | int | 黑点的下百分位（例如 10）。 |
| highPercentile | int | 白点的上百分位（例如 90）。 |
| targetWhite | int | 目标白色值（例如 240）。 |
|  | maxScale | float | 允许的最大亮度比例（例如 1.7）。 |

--------------------

该算法拉伸直方图，使白色百分位接近 `targetWhite`，但不超过 `maxScale`，以避免过度增亮。|

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


获取一个值，指示过滤器是否在灰度模式下运行。

**Returns:**
boolean - 指示过滤器是否在灰度模式下运行的值。
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


获取用于计算黑点的下百分位。拉伸过程中，低于该百分位的像素值被视为黑色。

**Returns:**
int - 用于计算黑点的下百分位。
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


获取用于计算白点的上百分位。拉伸过程中，高于该百分位的像素值被视为白色。

**Returns:**
int - 用于计算白点的上百分位。
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


获取拉伸目标的目标白色值。

**Returns:**
int - 拉伸目标的目标白色值。
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


获取允许的最大亮度比例。实际拉伸不会超过此因子，以避免过度增亮。

**Returns:**
float - 允许的最大亮度比例。
