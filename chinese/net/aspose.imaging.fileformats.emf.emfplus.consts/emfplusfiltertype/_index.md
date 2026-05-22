---
title: "枚举 EmfPlusFilterType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusFilterType 枚举。FilterType 枚举定义了可用于文本和图形质量提升以及图像渲染的过滤算法类型。"
type: docs
weight: 4920
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
## EmfPlusFilterType enumeration

FilterType 枚举定义可用于文本和图形质量提升以及图像渲染的过滤算法类型。

```csharp
public enum EmfPlusFilterType : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| FilterTypeNone | `0` | 指定不执行过滤。 |
| FilterTypePoint | `1` | 指定每个目标像素通过采样源图像中最近的像素来计算。 |
| FilterTypeLinear | `2` | 指定使用围绕源像素的 2x2 像素区域的加权平均进行线性插值。 |
| FilterTypeTriangle | `3` | 指定源图像中的每个像素对目标图像的贡献相等。这是最慢的过滤算法。 |
| FilterTypeBox | `4` | 指定一种盒式过滤算法，其中每个目标像素通过对源像素的矩形区域取平均来计算。此算法仅在缩小图像尺寸时有用。 |
| FilterTypePyramidalQuad | `6` | 指定使用 4 采样的帐篷滤波器。 |
| FilterTypeGaussianQuad | `7` | 指定使用 4 采样的高斯滤波器，它会在图像上产生模糊效果。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


