---
title: "类 EmfPlusDrawBeziers"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawBeziers 类。EmfPlusDrawBeziers 记录指定绘制一系列相连的贝塞尔曲线。贝塞尔数据点的顺序为起点、控制点 1、控制点 2 和终点。更多信息请参见 MSDNDrawBeziers。"
type: docs
weight: 6030
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
## EmfPlusDrawBeziers class

EmfPlusDrawBeziers 记录指定绘制一系列相连的贝塞尔曲线。贝塞尔数据点的顺序为起始点、控制点1、控制点2和终点。更多信息请参见 [MSDN-DrawBeziers]。

```csharp
public sealed class EmfPlusDrawBeziers : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawBeziers](emfplusdrawbeziers/)(EmfPlusRecord) | 初始化 `EmfPlusDrawBeziers` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/compressed/) { get; set; } | 获取或设置一个值，指示 PointData 是否已压缩。如果设置，则 PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，则 PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/objectid/) { get; set; } | 获取或设置对象标识符。它是 EMF+ 对象表中用于绘制贝塞尔曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/) { get; set; } | 获取或设置点数据。一个包含 Count 个点的数组，指定贝塞尔曲线的起点、终点和控制点。一个贝塞尔曲线的结束坐标是下一个贝塞尔曲线的起始坐标。控制点用于产生贝塞尔效果。此数组中的数据类型由 Flags 字段指定，如下所示： 数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节） 如果 Flags 中设置了 P 标志，则点指定相对位置。 EmfPlusPointF 对象（第 2.2.2.36 节） 如果 Flags 字段中的 P 和 C 位均未设置，则点指定绝对位置。 EmfPlusPoint 对象（第 2.2.2.35 节） 如果 Flags 中未设置 P 位且设置了 C 位，则点指定相对位置。贝塞尔曲线不会经过其控制点。控制点的作用是 |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/relative/) { get; set; } | 获取或设置一个值，指示 PointData 是否为相对的。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，则上面的 C 标志未定义，必须被忽略。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


