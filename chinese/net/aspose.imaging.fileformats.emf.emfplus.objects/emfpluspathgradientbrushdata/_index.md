---
title: "类 EmfPlusPathGradientBrushData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathGradientBrushData 类。EmfPlusPathGradientBrushData 对象指定用于图形画笔的路径渐变"
type: docs
weight: 5740
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
## EmfPlusPathGradientBrushData class

该 EmfPlusPathGradientBrushData 对象指定用于图形画刷的路径渐变。

```csharp
public sealed class EmfPlusPathGradientBrushData : EmfPlusBaseBrushData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusPathGradientBrushData](emfpluspathgradientbrushdata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BoundaryData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/boundarydata/) { get; set; } | 获取或设置路径渐变画笔的边界，该边界可以由路径或闭合的基数样条曲线指定。如果在 BrushDataFlags 字段中设置了 BrushDataPath 标志，则此字段必须包含一个 EmfPlusBoundaryPathData 对象（第 2.2.2.6 节）；否则，此字段必须包含一个 EmfPlusBoundaryPointData 对象（第 2.2.2.7 节）。 |
| [BrushDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/brushdataflags/) { get; set; } | 获取或设置 32 位无符号整数，指定 OptionalData 字段中的数据。该值必须由 BrushData 标志（第 2.1.2.1 节）组成。以下标志与路径渐变画笔相关： |
| [CenterArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerargb32color/) { get; set; } | 获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。画笔的颜色会从边界颜色逐渐过渡到中心颜色，随着从边界向中心点移动。 |
| [CenterPointF](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerpointf/) { get; set; } | 获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。画笔的颜色会从边界颜色逐渐过渡到中心颜色，随着从边界向中心点移动。 |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/optionaldata/) { get; set; } | 获取或设置可选的 EmfPlusPathGradientBrushOptionalData 对象（第 2.2.2.30 节），指定路径渐变画笔的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定。 |
| [SurroundingArgb32Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/surroundingargb32colors/) { get; set; } | 获取或设置 SurroundingColorCount 个 EmfPlusARGB 对象的数组，指定画笔边界上离散点的颜色。 |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/wrapmode/) { get; set; } | 获取或设置来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，指定是否绘制画笔边界之外的区域。在边界之外绘制时，包装模式指定颜色渐变的重复方式 |

### 另请参见

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


