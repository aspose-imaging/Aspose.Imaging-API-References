---
title: "类 EmfPlusDrawClosedCurve"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawClosedCurve 类。EmfPlusDrawClosedCurve 记录指定绘制闭合基数样条曲线。"
type: docs
weight: 6040
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

EmfPlusDrawClosedCurve 记录指定绘制闭合的基数样条曲线。

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve/)(EmfPlusRecord) | 初始化 `EmfPlusDrawClosedCurve` 类的新实例。RecordType - 一个 16 位无符号整数，用于标识此记录类型为来自 RecordType 枚举（第 2.1.1.1 节）的 EmfPlusDrawClosedCurve。该值必须为 0x4017。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed/) { get; set; } | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否被压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果清除，PointData 使用 32 位浮点坐标指定绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid/) { get; set; } | 获取或设置对象标识符。该索引是 EMF+ 对象表中用于绘制闭合曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/) { get; set; } | 获取或设置点数据。一个包含 Count 个点的数组，这些点指定定义样条曲线的线段的端点。在闭合基数样条中，曲线通过 PointData 数组中的最后一点继续，并与数组中的第一点相连。此数组中的数据类型由 Flags 字段指定，如下所示：数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节）如果 Flags 中设置了 P 标志，则点指定相对位置。EmfPlusPointF 对象（第 2.2.2.36 节）如果 Flags 字段中同时设置了 P 和 C 位，则点指定绝对位置。EmfPlusPoint 对象（第 2.2.2.35 节）如果 Flags 字段中 P 位未设置且 C 位已设置，则点指定相对位置。 |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative/) { get; set; } | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上述压缩标志未定义，必须被忽略。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension/) { get; set; } | 获取或设置张力。一个 32 位浮点数，指定样条曲线在经过各点时的弯曲程度。值为 0 表示样条是一系列直线。值越大，曲线越圆滑。更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


