---
title: "EmfPlusDrawClosedCurve 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | 初始化一个新的 [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) 类实例。<br/>            RecordType - 一个 16 位无符号整数，用于标识此记录类型为来自 RecordType 枚举（第 2.1.1.1 节）的 EmfPlusDrawClosedCurve。该值必须为 0x4017。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| compressed | bool | r/w | 获取或设置一个值，指示此 [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) 是否已压缩。<br/>            此位指示 PointData 字段是否指定压缩数据。<br/>            如果设置，则 PointData 指定坐标空间中使用 16 位整数坐标的绝对位置。 <br/>            如果未设置，则 PointData 指定坐标空间中使用 32 位浮点坐标的绝对位置<br/>            注意如果下面的 Relative 标志被设置，此标志未定义，必须被忽略 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            用于绘制闭合曲线的 EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置点数据<br/>            一个包含 Count 个点的数组，指定定义样条线的线段的端点。在闭合基数样条线中，<br/>            曲线通过 PointData 数组中的最后一点继续，并与数组中的第一点相连。<br/>            此数组中的数据类型由 Flags 字段指定，如下：数据类型 含义<br/>            EmfPlusPointR 对象（第 2.2.2.37 节）<br/>            如果 Flags 中设置了 P 标志，点表示相对位置。<br/>            EmfPlusPointF 对象（第 2.2.2.36 节）<br/>            如果 Flags 字段中同时设置了 P 和 C 位，点表示绝对位置。<br/>            EmfPlusPoint 对象（第 2.2.2.35 节）<br/>            如果 Flags 中未设置 P 位且设置了 C 位，点表示相对位置。 |
| relative | bool | r/w | 获取或设置一个值，指示此 [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) 是否为相对坐标。<br/>            此位指示 PointData 字段是指定相对位置还是绝对位置。<br/>            如果设置，则 PointData 中的每个元素指定坐标空间中相对于数组中前一个元素的位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，<br/>            PointData 根据 C 标志指定绝对位置。<br/>            注意如果此标志被设置，上面的 Compressed 标志未定义，必须被忽略 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| 张力 | float | r/w | 获取或设置张力<br/>            一个 32 位浮点数，指定样条线在通过各点时的弯曲程度。值为 0 表示样条线是一系列直线。随着值的增大，<br/>            曲线变得更圆滑。欲了解更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

初始化一个新的 [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) 类实例。<br/>            RecordType - 一个 16 位无符号整数，用于标识此记录类型为来自 RecordType 枚举（第 2.1.1.1 节）的 EmfPlusDrawClosedCurve。该值必须为 0x4017。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

