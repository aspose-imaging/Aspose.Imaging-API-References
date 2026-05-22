---
title: "EmfPlusDrawCurve 类"
type: docs
weight: 100
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | 初始化一个新的 [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| compressed | bool | r/w | 获取或设置一个值，指示此 [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) 是否已压缩。<br/>            此位指示 PointData 字段是否指定压缩数据。<br/>            如果设置，则 PointData 指定坐标空间中使用 16 位整数坐标的绝对位置。 <br/>            如果未设置，则 PointData 指定坐标空间中使用 32 位浮点坐标的绝对位置<br/>            注意如果下面的 Relative 标志被设置，此标志未定义，必须被忽略 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| num_segments | int | r/w | 获取或设置段计数 <br/>            一个 32 位无符号整数，指定构成样条的线段数量。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            在 EMF+<br/>            对象表中用于绘制曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置一个数组，数组由 32 位有符号整数或 32 位浮点数组成，<br/>            长度为 Count，定义要描边的线段端点的坐标值。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| 张力 | float | r/w | 获取或设置张力<br/>            一个 32 位浮点数，指定样条线在通过各点时的弯曲程度。值为 0 表示样条线是一系列直线。随着值的增大，<br/>            曲线变得更圆滑。欲了解更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

初始化一个新的 [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

