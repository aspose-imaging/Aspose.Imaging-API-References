---
title: "枚举 EmfPenStyle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfPenStyle 枚举。PenStyle 枚举定义了可用于图形操作的笔的属性。笔样式是笔类型、线型、线帽和线接合的组合。"
type: docs
weight: 2870
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
## EmfPenStyle enumeration

该 PenStyle 枚举定义了可用于图形操作的笔的属性。笔样式是笔类型、线型、线帽和线接的组合。

```csharp
[Flags]
public enum EmfPenStyle
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PS_COSMETIC | `0` | 一种笔类型，指定宽度为一个逻辑单元且样式为纯色的线条。 |
| PS_ENDCAP_ROUND | `0` | 一种线帽，指定圆形端点。 |
| PS_JOIN_ROUND | `0` | 一种线接合，指定圆形连接。 |
| PS_SOLID | `0` | 一种线型，为纯色。 |
| PS_DASH | `1` | 一种线型，为虚线。 |
| PS_DOT | `2` | 一种点状的线型。 |
| PS_DASHDOT | `3` | 一种由交替的短划线和点组成的线型 |
| PS_DASHDOTDOT | `4` | 一种由短划线和双点组成的线型。 |
| PS_NULL | `5` | 一种不可见的线型。 |
| PS_INSIDEFRAME | `6` | 一种实色的线型。当在接受边界矩形的绘图记录中指定此线型时，图形的尺寸会被缩小，以便完全适应边界矩形，并考虑到笔的宽度。 |
| PS_USERSTYLE | `7` | 一种由样式数组定义的线型，该数组指定线段中短划线和间隙的长度 |
| PS_ALTERNATE | `8` | 一种每隔一个像素设置的线型。此线型仅适用于 PS_COSMETIC 笔类型 |
| PS_ENDCAP_SQUARE | `100` | 一种指定方形端点的线帽。 |
| PS_ENDCAP_FLAT | `200` | 一种指定平直端点的线帽。 |
| PS_JOIN_BEVEL | `1000` | 一种指定斜角连接的线段连接方式。 |
| PS_JOIN_MITER | `2000` | 一种在连接长度在播放设备上下文中设置的当前斜接长度限制范围内时指定斜接连接的线段连接方式。如果连接长度超过斜接限制，则指定斜角连接。 |
| PS_GEOMETRIC | `10000` | 一种笔类型，指定以逻辑单位测量宽度的线，并且其样式可以包含画刷的任何属性。 |
| StyleMask | `F` | 样式掩码 |
| EndCapMask | `F00` | 端帽掩码 |
| JoinMask | `F000` | 连接掩码 |
| TypeMask | `F0000` | 类型掩码 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


