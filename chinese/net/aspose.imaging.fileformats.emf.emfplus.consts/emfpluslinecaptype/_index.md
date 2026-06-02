---
title: "枚举 EmfPlusLineCapType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusLineCapType 枚举。LineCapType 枚举定义使用图形笔绘制的线段末端的线帽类型。"
type: docs
weight: 5010
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
## EmfPlusLineCapType enumeration

LineCapType 枚举定义了使用图形笔绘制的线段末端的线帽类型。

```csharp
public enum EmfPlusLineCapType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| LineCapTypeFlat | `0` | 指定方形线帽。线段的末端必须是线的最后一个点。 |
| LineCapTypeSquare | `1` | 指定方形线帽。方形的中心必须位于线的最后一个点。方形的宽度等于线宽。 |
| LineCapTypeRound | `2` | 指定圆形线帽。圆心必须位于线的最后一个点。圆的直径等于线宽。 |
| LineCapTypeTriangle | `3` | 指定三角形线帽。三角形的底部必须位于线的最后一个点。三角形的底宽等于线宽。 |
| LineCapTypeNoAnchor | `16` | 指定线端未锚定。 |
| LineCapTypeSquareAnchor | `17` | 指定线端使用方形线帽锚定。方形的中心必须位于线的最后一个点。方形的高度和宽度等于线宽。 |
| LineCapTypeRoundAnchor | `18` | 指定线端使用圆形线帽锚定。圆心必须位于线的最后一个点。圆的宽度应大于线宽。 |
| LineCapTypeDiamondAnchor | `19` | 指定线端使用菱形线帽锚定，菱形是旋转 45 度的方形。菱形的中心必须位于线的最后一个点。菱形的宽度应大于线宽。 |
| LineCapTypeArrowAnchor | `20` | 指定线段末端使用箭头形状锚定。箭头尖端必须位于线段的最后一点。箭头的宽度应大于线段的宽度。 |
| LineCapTypeAnchorMask | `240` | 用于检查线帽是否为锚定帽的掩码。 |
| LineCapTypeCustom | `255` | 指定自定义线帽。 |

## 备注

图形线帽由 [`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen/) 对象指定（第 2.2.1.7 节）。

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


