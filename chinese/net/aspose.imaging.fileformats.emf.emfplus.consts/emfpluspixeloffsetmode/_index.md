---
title: "枚举 EmfPlusPixelOffsetMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPixelOffsetMode 枚举。PixelOffsetMode 枚举定义像素的偏移方式，指定渲染速度与质量之间的取舍。"
type: docs
weight: 5140
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
## EmfPlusPixelOffsetMode enumeration

PixelOffsetMode 枚举定义了像素的偏移方式，指定了渲染速度与质量之间的权衡。

```csharp
public enum EmfPlusPixelOffsetMode : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PixelOffsetModeDefault | `0` | 像素居中于整数坐标，优先速度而非质量。 |
| PixelOffsetModeHighSpeed | `1` | 像素居中于整数坐标，与 PixelOffsetModeNone 相同。指定以更高速度为代价牺牲质量。 |
| PixelOffsetModeHighQuality | `2` | 像素居中于半整数坐标，与 PixelOffsetModeHalf 相同。指定以更高质量为代价牺牲速度。 |
| PixelOffsetModeNone | `3` | 像素居中于原点，这意味着像素在 x、y 轴上覆盖 -0.5 到 0.5 的区域，中心位于 (0,0)。 |
| PixelOffsetModeHalf | `4` | 像素居中于半整数坐标，这意味着像素在 x、y 轴上覆盖 0 到 1 的区域，中心位于 (0.5,0.5)。在渲染过程中偏移像素可以提升渲染质量，但会降低渲染速度。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


