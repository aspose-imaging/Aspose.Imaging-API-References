---
title: "类 EmfPlusDrawArc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawArc 类。EmfPlusDrawArc 记录指定绘制椭圆的弧线"
type: docs
weight: 6020
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
## EmfPlusDrawArc class

EmfPlusDrawArc 记录指定绘制椭圆的弧线。

```csharp
public sealed class EmfPlusDrawArc : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawArc](emfplusdrawarc/)(EmfPlusRecord) | 初始化 `EmfPlusDrawArc` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/datasize/) { get; set; } | 获取或设置数据的大小。一个 32 位无符号整数，指定随后记录特定数据的 32 位对齐字节数。对于此记录类型，值必须是以下之一：0x00000010（如果 Flags 字段中的 C 位被设置）。0x00000018（如果 Flags 字段中的 C 位被清除）。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/objectid/) { get; set; } | 获取或设置对象标识符。用于绘制弧线的 EMF+ 对象表中 EmfPlusPen 对象（章节 2.2.1.7）的索引。该值必须在 0 到 63（含）之间。 |
| [RectangleData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectangledata/) { get; set; } | 获取或设置矩形数据。可以是定义与弧线共线的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。此矩形定义弧线的位置、大小和形状。该字段中对象的类型由 Flags 字段的值指定。 |
| [RectFloat](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectfloat/) { get; set; } | 获取或设置一个值，指示数据是包含 EmfPlusRectF 还是 EmfPlusRect 记录。此位指示 RectData 字段中的数据是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（章节 2.2.2.38）。如果清除，则 RectData 包含 EmfPlusRectF 对象（章节 2.2.2.39）。 |
| override [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/size/) { get; set; } | 获取或设置大小。一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。对于此记录类型，值必须是以下之一：0x0000001C（如果 Flags 字段中的 C 位被设置）。0x00000024（如果 Flags 字段中的 C 位被清除）。 |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/startangle/) { get; set; } | 获取或设置起始角度。一个 32 位非负浮点值，指定 x 轴与弧线起始点之间的角度。任何值均可接受，但必须对 360 取模，使用的结果应在 0.0（含）到 360.0（不含）之间。 |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/sweepangle/) { get; set; } | 获取或设置扫掠角度。一个 32 位浮点值，指定要绘制的弧线范围，以度数表示，从 StartAngle 值定义的起始点测量。任何值均可接受，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


