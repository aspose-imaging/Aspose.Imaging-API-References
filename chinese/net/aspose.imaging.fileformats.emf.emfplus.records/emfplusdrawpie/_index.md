---
title: "类 EmfPlusDrawPie"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawPie 类。EmfPlusDrawPie 记录指定绘制椭圆内部的一段。"
type: docs
weight: 6120
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
## EmfPlusDrawPie class

EmfPlusDrawPie 记录指定绘制椭圆内部的一个扇形。

```csharp
public sealed class EmfPlusDrawPie : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawPie](emfplusdrawpie/)(EmfPlusRecord) | 初始化 `EmfPlusDrawPie` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/compressed/) { get; set; } | 获取或设置一个值，指示 PointData 是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果清除，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/objectid/) { get; set; } | 获取或设置对象标识符。用于绘制饼形的 EMF+ 对象表中 EmfPlusPen 对象（章节 2.2.1.7）的索引。该值必须在 0 到 63（含）之间。 |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/rectdata/) { get; set; } | 获取或设置矩形数据。可以是定义包含饼形楔的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。此矩形定义饼形的位置、大小和形状。此字段中的对象类型由 Flags 字段的值指定。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/startangle/) { get; set; } | 获取或设置起始角度。一个 32 位非负浮点值，指定 x 轴与饼形楔起始点之间的角度。任何值均可接受，但必须对 360 取模，结果应在 0.0（含）到 360.0（不含）之间。 |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/sweepangle/) { get; set; } | 获取或设置扫掠角度。一个 32 位浮点值，指定绘制饼形楔的弧度范围，以度数表示，测量自 StartAngle 值定义的起始点。任何值均可接受，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


