---
title: "EmfPlusDrawBeziers 类"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | 初始化一个新的 [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 已压缩 | bool | r/w | 获取或设置一个值，以指示 PointData 是否已压缩。<br/>            如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。<br/>            如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。<br/>            注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节）的索引，用于绘制贝塞尔曲线。该值必须在 0 到 63（含）之间。 |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置点数据<br/>            一个 Count 点数组，指定贝塞尔曲线的起始、结束和控制点。一个贝塞尔曲线的结束坐标是下一个曲线的起始坐标。控制点用于产生贝塞尔效果。<br/>            此数组中数据的类型由 Flags 字段指定，如下：数据类型 含义<br/>            EmfPlusPointR 对象（第 2.2.2.37 节）<br/>            如果 Flags 中的 P 标志被设置，点指定相对位置。<br/>            EmfPlusPointF 对象（第 2.2.2.36 节）<br/>            如果 Flags 字段中的 P 和 C 位均未设置，点指定绝对位置。<br/>            EmfPlusPoint 对象（第 2.2.2.35 节）<br/>            如果 Flags 中的 P 位未设置且 C 位被设置，点指定相对位置。<br/>            贝塞尔曲线不会经过其控制点。控制点的作用是 |
| relative | bool | r/w | 获取或设置一个值，指示 PointData 是否为相对坐标。<br/>            如果设置，则 PointData 中的每个元素指定坐标空间中的一个位置，<br/>            该位置相对于数组中前一个元素指定的位置。<br/>            对于 PointData 的第一个元素，假定前一个位置的坐标为 (0,0)。如果未设置，PointData 根据 C 标志指定绝对位置。<br/>            注意：如果此标志被设置，上述 C 标志未定义，必须忽略。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

初始化一个新的 [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

