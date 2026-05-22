---
title: "类 EmfPlusHatchBrushData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusHatchBrushData 类。EmfPlusHatchBrushData 对象指定用于图形画笔的交叉图案"
type: docs
weight: 5600
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
## EmfPlusHatchBrushData class

EmfPlusHatchBrushData 对象指定图形刷的交叉图案。

```csharp
public sealed class EmfPlusHatchBrushData : EmfPlusBaseBrushData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusHatchBrushData](emfplushatchbrushdata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/backargb32color/) { get; set; } | 获取或设置一个 32 位 EmfPlusArgb 对象，该对象指定用于绘制交叉图案背景的颜色。 |
| [ForeArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/foreargb32color/) { get; set; } | 获取或设置一个 32 位 EmfPlusArgb 对象，该对象指定用于绘制交叉图案线条的颜色。 |
| [HatchStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/hatchstyle/) { get; set; } | 获取或设置一个 32 位无符号整数，指定画笔的交叉样式。它必须在 [`EmfPlusHatchStyle`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfplushatchstyle/) 枚举中定义。 |

## 备注

图形画笔由 [`EmfPlusBrush`](../emfplusbrush/) 对象（第 2.2.1.1 节）指定。交叉画笔在背景上绘制背景并绘制线条、点、短划线、方块和交叉线的图案。交叉画笔定义了两种颜色：一种用于背景，另一种用于背景上的图案。背景的颜色称为背景色，图案的颜色称为前景色。

### 另请参见

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


