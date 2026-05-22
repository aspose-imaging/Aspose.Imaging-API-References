---
title: "EmfPlusSetClipPath 类"
type: docs
weight: 460
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---

**Summary:** The EmfPlusSetClipPath record combines the current clipping region with a graphics path.<br/>            The new current clipping region is set to the result of the CombineMode operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipPath

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetClipPath(source)](#EmfPlusSetClipPath_source_1) | 初始化 [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | 获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。请参阅<br/>            CombineMode 枚举（第 2.1.1.4 节）以了解各取值的含义。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| object_id | System.Byte | r/w | 获取或设置 EMF+ 对象表中 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetClipPath(source) {#EmfPlusSetClipPath_source_1}


```
 EmfPlusSetClipPath(source) 
```

初始化 [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

