---
title: "EmfPlusFillRects 类"
type: docs
weight: 280
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---

**Summary:** The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusFillRects(source)](#EmfPlusFillRects_source_1) | 初始化一个新的 [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_id | int | r/w | 获取或设置画笔标识符<br/>            一个 32 位无符号整数，用于定义画笔，其内容由 Flags 字段中的 S 位决定。 |
| compressed | bool | r/w | 获取或设置一个值，指示此 [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) 是否被压缩。<br/>            如果设置，则 RectData 包含一个 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData<br/>            包含一个 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| is_color | bool | r/w | 获取或设置一个值，指示此实例是否为颜色。<br/>            如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。<br/>            如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置矩形数据<br/>            一个长度为 Count 的数组，包含 EmfPlusRect 或 EmfPlusRectF 对象，用于定义矩形数据。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusFillRects(source) {#EmfPlusFillRects_source_1}


```
 EmfPlusFillRects(source) 
```

初始化一个新的 [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

