---
title: "类 EmfPlusDrawLines"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawLines 类。EmfPlusDrawlLines 记录指定绘制一系列相连的线条。"
type: docs
weight: 6100
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
## EmfPlusDrawLines class

EmfPlusDrawlLines 记录指定绘制一系列相连的直线。

```csharp
public sealed class EmfPlusDrawLines : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawLines](emfplusdrawlines/)(EmfPlusRecord) | 初始化 `EmfPlusDrawLines` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ClosedShape](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/closedshape/) { get; set; } | 获取或设置一个值，指示 [closed shape]。 |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/compressed/) { get; set; } | 获取或设置一个值，指示此 [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 指定使用 16 位整数坐标的坐标空间中的绝对位置。如果清除，PointData 指定使用 32 位浮点坐标的坐标空间中的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/objectid/) { get; set; } | 获取或设置对象标识符。EMF+ 对象表中用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/pointdata/) { get; set; } | 获取或设置点数据。一个包含 Count 点的数组，指定要绘制的线条的起始和结束点。 |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/relative/) { get; set; } | 获取或设置一个值，指示此 [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。对于 PointData 的第一个元素，假设前一个位置为坐标 (0,0)。如果清除，PointData 按照 C 标志指定绝对位置。注意：如果此标志被设置，上面的 Compressed 标志未定义，必须被忽略。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


