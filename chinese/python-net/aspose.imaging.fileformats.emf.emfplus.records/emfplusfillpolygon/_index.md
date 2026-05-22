---
title: "EmfPlusFillPolygon 类"
type: docs
weight: 270
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | 初始化一个新的 [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_id | int | r/w | 获取或设置画笔标识符<br/>            一个 32 位无符号整数，用于定义画笔，其内容<br/>            由 Flags 字段中的 S 位决定。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| is_color | bool | r/w | 获取或设置一个值，指示此实例是否为颜色。<br/>            若设置，则 BrushId 以 EmfPlusARGB 对象（第 2.2.2.1 节）指定颜色。<br/>            若未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| is_compressed | bool | r/w | 获取或设置一个值，指示此实例是否已压缩。<br/>            若设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。<br/>            若未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。 |
| is_relative | bool | r/w | 获取或设置一个值，指示此实例是否为相对坐标。<br/>            若设置，PointData 中的每个元素指定相对于数组中前一个元素所在坐标空间的位置。<br/>            对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。<br/>            若未设置，PointData 按照 C 标志指定绝对位置。 |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置点数据<br/>            一个包含 Count 个点的数组，用于定义多边形的顶点。<br/>            数组中的前两个点指定多边形的第一条边。<br/>            每个后续点指定一条新边，其顶点包括该点和前一个点。<br/>            如果最后一个点和第一个点不重合，则它们构成多边形的最后一条边。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

初始化一个新的 [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

