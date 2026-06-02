---
title: "类 EmfPlusDrawCurve"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawCurve 类。EmfPlusDrawCurve 记录指定绘制基数样条。注意：ObjectID 为 1 字节，表示 EMF 对象表中第 2.2.1.7 节的 EmfPlusPen 对象的索引，用于绘制曲线。该值必须在 0 到 63（含）之间。"
type: docs
weight: 6050
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
## EmfPlusDrawCurve class

EmfPlusDrawCurve 记录指定绘制基数样条曲线。注意：ObjectID（1 字节）：在 EMF+ 对象表中用于绘制曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

```csharp
public sealed class EmfPlusDrawCurve : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawCurve](emfplusdrawcurve/)(EmfPlusRecord) | 初始化 `EmfPlusDrawCurve` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/compressed/) { get; set; } | 获取或设置一个值，指示此 [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 指定使用 16 位整数坐标的坐标空间中的绝对位置。如果清除，PointData 指定使用 32 位浮点坐标的坐标空间中的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [NumSegments](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/numsegments/) { get; set; } | 获取或设置段计数，一个 32 位无符号整数，指定构成样条的线段数量。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/objectid/) { get; set; } | 获取或设置对象标识符。该标识符是 EMF+ 对象表中用于绘制曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/pointdata/) { get; set; } | 获取或设置一个长度为 Count 的数组，数组元素可以是 32 位有符号整数或 32 位浮点数，用于定义要描边的线段端点的坐标值。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/tension/) { get; set; } | 获取或设置张力。一个 32 位浮点数，指定样条曲线在经过各点时的弯曲程度。值为 0 表示样条是一系列直线。值越大，曲线越圆滑。更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


