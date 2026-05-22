---
title: "枚举 EmfPlusCompositingQuality"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCompositingQuality 枚举。CompositingQuality 枚举定义了创建复合图像的质量级别。"
type: docs
weight: 4850
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
## EmfPlusCompositingQuality enumeration

CompositingQuality 枚举定义创建复合图像的质量级别

```csharp
public enum EmfPlusCompositingQuality : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| CompositingQualityDefault | `1` | 不执行伽马校正。伽马校正控制图像的整体亮度和对比度。若不进行伽马校正，合成图像可能显得过亮或过暗。 |
| CompositingQualityHighSpeed | `2` | 不执行伽马校正。合成速度优先于质量。就结果而言，此值与 CompositingQualityDefault 没有区别。 |
| CompositingQualityHighQuality | `3` | 执行伽马校正。合成质量优先于速度。 |
| CompositingQualityGammaCorrected | `4` | 启用伽马校正以获得更高质量但速度较慢的合成。就结果而言，此值与 CompositingQualityHighQuality 没有区别。 |
| CompositingQualityAssumeLinear | `5` | 不执行伽马校正；然而，使用线性值在稍低的速度下可获得比默认更好的质量。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


