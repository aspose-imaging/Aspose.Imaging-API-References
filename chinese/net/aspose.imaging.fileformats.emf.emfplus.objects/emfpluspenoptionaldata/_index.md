---
title: "类 EmfPlusPenOptionalData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPenOptionalData 类。EmfPlusPenOptionalData 对象指定图形笔的可选数据。"
type: docs
weight: 5800
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

该 EmfPlusPenOptionalData 对象指定图形笔的可选数据。

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata/) { get; set; } | 获取或设置可选的 EmfPlusCompoundLineData 对象（第 2.2.2.9 节），该对象指定一个浮点值数组，用于定义笔的复合线，由平行线和间隔组成。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCompoundLine 标志，则此字段必须存在。 |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata/) { get; set; } | 获取或设置可选的 EmfPlusCustomEndCapData 对象（第 2.2.2.11 节），该对象定义自定义结束帽形状，即使用此笔绘制的线段末端的形状。它可以是各种形状，如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomEndCap 标志，则此字段必须存在。 |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata/) { get; set; } | 获取或设置可选的 EmfPlusCustomStartCapData 对象（第 2.2.2.15 节），该对象定义自定义起始帽形状，即使用此笔绘制的线段起始端的形状。它可以是各种形状，如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomStartCap 标志，则此字段必须存在。 |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype/) { get; set; } | 获取或设置可选的 32 位有符号整数，指定虚线中每个短划线两端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineCap 标志，则此字段必须存在，且该值必须在 DashedLineCapType 枚举（第 2.1.1.10 节）中定义。 |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata/) { get; set; } | 获取或设置可选的 EmfPlusDashedLineData 对象（第 2.2.2.16 节），该对象指定自定义虚线中短划线和间隔的长度。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLine 标志，则此字段必须存在。 |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset/) { get; set; } | 获取或设置可选的 32 位浮点值，指定从直线起点到虚线模式中第一个空格起点的距离。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineOffset 标志，则此字段必须存在。 |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap/) { get; set; } | 获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段末端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataEndCap 标志，则此字段必须存在，且该值必须在 LineCapType 枚举中定义。 |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join/) { get; set; } | 获取或设置可选的 32 位有符号整数，指定使用同一支笔绘制且端点相接的两条线的连接方式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataJoin 标志，则此字段必须存在，且该值必须在 LineJoinType 枚举（第 2.1.1.19 节）中定义。 |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle/) { get; set; } | 获取或设置可选的 32 位有符号整数，指定使用此笔对象绘制的线条样式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataLineStyle 标志，则此字段必须存在，且该值必须在 LineStyle 枚举（第 2.1.1.20 节）中定义。 |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit/) { get; set; } | 获取或设置可选的 32 位浮点值，指定斜接限制，即斜接长度与线宽的最大允许比例。斜接长度是指连接内部线壁交点到连接外部线壁交点的距离。当两条线的夹角较小时，斜接长度可能会很大。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataMiterLimit 标志，则此字段必须存在。 |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment/) { get; set; } | 获取或设置可选的 32 位有符号整数，指定相对于被绘制线条坐标的笔宽分布。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataNonCenter 标志，则此字段必须存在，且该值必须在 PenAlignment 枚举（第 2.1.1.24 节）中定义。 |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap/) { get; set; } | 获取或设置可选的 32 位有符号整数，指定 CustomStartCapData 字段中线段起始端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataStartCap 标志，则此字段必须存在，且该值必须在 LineCapType 枚举（第 2.1.1.18 节）中定义。 |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix/) { get; set; } | 获取或设置可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定笔的世界坐标到设备坐标的变换。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataTransform 标志，则此字段必须存在。 |

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


