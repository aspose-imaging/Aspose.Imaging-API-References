---
title: "枚举 InterpolationMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.InterpolationMode 枚举。InterpolationMode 枚举指定在对图像进行缩放或旋转时使用的算法。"
type: docs
weight: 10730
url: /zh/net/aspose.imaging/interpolationmode/
---
## InterpolationMode enumeration

`InterpolationMode` 枚举指定在对图像进行缩放或旋转时使用的算法。

```csharp
public enum InterpolationMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Invalid | `-1` | 无效的插值模式。 |
| Default | `0` | 指定默认模式。 |
| Low | `1` | 指定低质量插值。 |
| High | `2` | 指定高质量插值。 |
| Bilinear | `3` | 指定双线性插值。未进行预过滤。此模式不适用于将图像缩小至原始大小的 50% 以下。 |
| Bicubic | `4` | 指定双三次插值。未进行预过滤。此模式不适用于将图像缩小至原始大小的 25% 以下。 |
| NearestNeighbor | `5` | 指定最近邻插值。 |
| HighQualityBilinear | `6` | 指定高质量双线性插值。进行预过滤以确保高质量的缩小。 |
| HighQualityBicubic | `7` | 指定高质量双三次插值。进行预过滤以确保高质量的缩小。此模式产生最高质量的变换图像。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


