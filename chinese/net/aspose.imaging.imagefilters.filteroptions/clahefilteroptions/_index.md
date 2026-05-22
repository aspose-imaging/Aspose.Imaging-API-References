---
title: "类 ClaheFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageFilters.FilterOptions.ClaheFilterOptions 类。提供用于配置对比度受限自适应直方图均衡 CLAHE 滤镜的选项"
type: docs
weight: 9990
url: /zh/net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
## ClaheFilterOptions class

提供配置对比度受限自适应直方图均衡（CLAHE）滤镜的选项。

```csharp
public class ClaheFilterOptions : FilterOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ClaheFilterOptions](clahefilteroptions/)(bool, int, int, double) | 使用指定的参数初始化 `ClaheFilterOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ClipLimit](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/cliplimit/) { get; } | 获取对比度限制阈值。较高的值允许更大的对比度；较低的值限制增强以防止噪声放大。 |
| [IsGrayscale](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/isgrayscale/) { get; } | 获取一个值，指示滤镜是否在灰度模式下运行。 |
| [TilesNumberHorizontal](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/tilesnumberhorizontal/) { get; } | 获取水平方向的瓦片数量。决定图像在局部对比度均衡时水平划分为多少个区域。 |
| [TilesNumberVertical](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/tilesnumbervertical/) { get; } | 获取垂直方向的瓦片数量。决定图像在局部对比度均衡时垂直划分为多少个区域。 |

### 另请参见

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


