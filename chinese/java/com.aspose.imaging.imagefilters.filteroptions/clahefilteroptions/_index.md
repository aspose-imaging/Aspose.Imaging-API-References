---
title: "ClaheFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "提供用于配置对比度受限自适应直方图均衡（CLAHE）滤波器的选项。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

提供用于配置 Contrast-Limited Adaptive Histogram Equalization (CLAHE) 滤镜的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | 使用指定的参数初始化 [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | 获取一个值，指示过滤器是否在灰度模式下运行。 |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | 获取水平方向的瓦片数量。 |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | 获取垂直方向的瓦片数量。 |
| [getClipLimit()](#getClipLimit--) | 获取对比度限制阈值。 |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


使用指定的参数初始化 [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isGrayscale | boolean | 指示过滤器是否应在灰度模式下运行。 |
| tilesNumberHorizontal | int | 水平瓦片数量。默认值为 8。 |
| tilesNumberVertical | int | 垂直瓦片数量。默认值为 8。 |
| clipLimit | double | 对比度限制阈值。默认值为 4.0。 |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


获取一个值，指示过滤器是否在灰度模式下运行。

**Returns:**
boolean - 指示过滤器是否在灰度模式下运行的值。
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


获取水平方向上的瓦片数量。确定图像在局部对比度均衡时水平划分为多少个区域。

**Returns:**
int - 水平方向上的瓦片数量。
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


获取垂直方向上的瓦片数量。确定图像在局部对比度均衡时垂直划分为多少个区域。

**Returns:**
int - 垂直方向上的瓦片数量。
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


获取对比度限制阈值。较高的值允许更大的对比度；较低的值限制增强以防止噪声放大。

**Returns:**
double - 对比度限制阈值。
