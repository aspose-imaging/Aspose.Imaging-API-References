---
title: "EmfPlusDrawPath 类"
type: docs
weight: 160
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---

**Summary:** The EmfPlusDrawPath record specifies drawing a graphics path.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawPath(source)](#EmfPlusDrawPath_source_1) | 初始化一个新的 [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            在<br/>            EMF+ 对象表中用于绘制的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。 |
| pen_id | int | r/w | 获取或设置笔标识符<br/>            一个 32 位无符号整数，指定 EMF+ 对象表中用于绘制 EmfPlusPath 的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。<br/>            该值必须在 0 到 63（含）之间 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawPath(source) {#EmfPlusDrawPath_source_1}


```
 EmfPlusDrawPath(source) 
```

初始化一个新的 [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

