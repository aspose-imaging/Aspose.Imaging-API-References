---
title: "EmfPlusFillPath 类"
type: docs
weight: 250
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---

**Summary:** Fill path record<br/>            FLAGS:<br/>            16-bit unsigned integer that provides information about how the operation is to be performed,<br/>            and about the structure of the record.<br/>            0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            S X X X X X X X |   ObjectId    |<br/>            S (1 bit): This bit indicates the type of data in the BrushId field.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.<br/>            X (1 bit): Reserved and MUST be ignored.<br/>            ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusFillPath(source)](#EmfPlusFillPath_source_1) | 初始化一个新的 [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_id | int | r/w | 获取或设置 Brush ID<br/>            一个 32 位无符号整数，用于定义画笔，其内容由 Flags 字段中的 S 位决定。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| is_color | bool | r/w | 获取或设置一个值，指示此实例是否为颜色。<br/>            如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）中的颜色。如果未设置，<br/>            BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            要填充的 EmfPlusPath 对象（第 2.2.1.6 节）在 EMF+ 对象表中的索引。该值必须在 0 到 63（含）之间。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusFillPath(source) {#EmfPlusFillPath_source_1}


```
 EmfPlusFillPath(source) 
```

初始化一个新的 [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

