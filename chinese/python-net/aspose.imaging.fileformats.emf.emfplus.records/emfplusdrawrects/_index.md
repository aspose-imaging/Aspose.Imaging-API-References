---
title: "EmfPlusDrawRects 类"
type: docs
weight: 180
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---

**Summary:** The EmfPlusDrawRects record specifies drawing a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawRects(source)](#EmfPlusDrawRects_source_1) | 初始化 [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 已压缩 | bool | r/w | 获取或设置一个值，指示 PointData 是否已压缩。<br/>            如果设置，RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。<br/>            如果未设置，RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            EMF+ 对象表中用于绘制矩形的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置矩形数据<br/>            一个由 EmfPlusRect 或 EmfPlusRectF 对象组成、长度为 Count 的数组，用于定义矩形数据。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawRects(source) {#EmfPlusDrawRects_source_1}


```
 EmfPlusDrawRects(source) 
```

初始化 [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

