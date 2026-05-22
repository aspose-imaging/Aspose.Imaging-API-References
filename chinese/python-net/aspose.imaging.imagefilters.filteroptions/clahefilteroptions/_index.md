---
title: "ClaheFilterOptions 类"
type: docs
weight: 50
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | 初始化 [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) 类的新实例<br/>            使用指定的参数。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| clip_limit | float | r | 获取对比度限制阈值。<br/>            较高的值允许更高的对比度；较低的值限制增强以防止噪声放大。 |
| is_grayscale | bool | r | 获取一个值，指示过滤器是否在灰度模式下运行。 |
| tiles_number_horizontal | int | r | 获取水平方向上的瓦片数量。<br/>            确定图像在水平上被划分为多少个区域，以进行局部对比度均衡。 |
| tiles_number_vertical | int | r | 获取垂直方向上的瓦片数量。<br/>            确定图像在垂直上被划分为多少个区域，以进行局部对比度均衡。 |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

初始化 [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) 类的新实例<br/>            使用指定的参数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| is_grayscale | bool | 指示过滤器是否应在灰度模式下运行。 |
| tiles_number_horizontal | int | 水平瓦片数量。默认值为 8。 |
| tiles_number_vertical | int | 垂直瓦片数量。默认值为 8。 |
| clip_limit | float | 对比度限制阈值。默认值为 4.0。 |

