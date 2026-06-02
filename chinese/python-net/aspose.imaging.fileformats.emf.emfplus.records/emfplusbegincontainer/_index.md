---
title: "EmfPlusBeginContainer 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---

**Summary:** The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusBeginContainer(source)](#EmfPlusBeginContainer_source_1) | 初始化一个新的 [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| dest_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置一个 EmfPlusRectF 对象（章节 2.2.2.39），它与 SrcRect 一起指定容器的变换。该变换在应用于 DestRect 时产生 SrcRect。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | 获取页面单位。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置一个 EmfPlusRectF 矩形，它与 DestRect 一起指定容器的变换。该变换在应用于 DestRect 时产生 SrcRect。 |
| stack_index | int | r/w | 获取或设置一个 32 位无符号整数，用于指定与<br/>图形状态容器关联的索引。该索引必须在后续的<br/>EmfPlusEndContainer 记录（第 2.3.7.3 节）中被引用，以关闭图形状态容器。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusBeginContainer(source) {#EmfPlusBeginContainer_source_1}


```
 EmfPlusBeginContainer(source) 
```

初始化一个新的 [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

