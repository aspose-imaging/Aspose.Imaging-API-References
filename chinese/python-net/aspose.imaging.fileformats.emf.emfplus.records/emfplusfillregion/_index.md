---
title: "EmfPlusFillRegion 类"
type: docs
weight: 290
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---

**Summary:** The EmfPlusFillRegion record specifies filling the interior of a graphics region

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRegion

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusFillRegion(source)](#EmfPlusFillRegion_source_1) | 初始化一个新的 [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_id | int | r/w | 获取或设置画笔标识符<br/>            一个 32 位无符号整数，用于定义画笔，其内容由 Flags 字段中的 S 位决定。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| is_color | bool | r/w | 获取或设置一个值，指示此实例是否为颜色。<br/>            若设置，则 BrushId 以 EmfPlusARGB 对象（第 2.2.2.1 节）指定颜色。<br/>            若未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            在<br/>            EMF+ 对象表中用于填充的 EmfPlusRegion 对象（第 2.2.1.8 节）的索引。该值必须在 0 到 63（含）之间。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusFillRegion(source) {#EmfPlusFillRegion_source_1}


```
 EmfPlusFillRegion(source) 
```

初始化一个新的 [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

