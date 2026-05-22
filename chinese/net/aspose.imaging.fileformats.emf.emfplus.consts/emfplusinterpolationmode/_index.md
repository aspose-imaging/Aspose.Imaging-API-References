---
title: "枚举 EmfPlusInterpolationMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusInterpolationMode 枚举。InterpolationMode 枚举定义了执行缩放（包括拉伸和收缩）的方法。"
type: docs
weight: 4990
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
## EmfPlusInterpolationMode enumeration

InterpolationMode 枚举定义执行缩放的方式，包括拉伸和收缩。

```csharp
public enum EmfPlusInterpolationMode : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| InterpolationModeDefault | `0` | 指定默认插值模式，定义为 InterpolationModeBilinear。 |
| InterpolationModeLowQuality | `1` | 指定低质量插值模式，定义为 InterpolationModeNearestNeighbor。 |
| InterpolationModeHighQuality | `2` | 指定高质量插值模式，定义为 InterpolationModeHighQualityBicubic。 |
| InterpolationModeBilinear | `3` | 指定双线性插值，它使用围绕待插值像素的最近 2×2 像素邻域。对这 4 个已知像素值进行加权平均，以确定分配给插值像素的值。其结果比 InterpolationModeNearestNeighbor 更平滑。 |
| InterpolationModeBicubic | `4` | 指定双三次插值，它使用围绕插值像素的最近的4x4已知像素邻域。对这16个已知像素值的加权平均决定要分配给插值像素的值。由于已知像素与插值像素的距离可能不同，较近的像素在计算中权重更高。结果比 InterpolationModeBilinear 更平滑。 |
| InterpolationModeNearestNeighbor | `5` | 指定最近邻插值，它仅使用最接近插值像素的像素值。此模式仅复制或删除像素，在这些选项中产生最低质量的结果。 |
| InterpolationModeHighQualityBilinear | `6` | 指定带预过滤的双线性插值。 |
| InterpolationModeHighQualityBicubic | `7` | 指定带预过滤的双三次插值，它在这些选项中产生最高质量的结果。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


