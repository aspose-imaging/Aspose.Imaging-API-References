---
title: "EmfPlusBeginContainerNoParams 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---

**Summary:** The EmfPlusBeginContainerNoParams record opens a new graphics state container.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainerNoParams

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusBeginContainerNoParams(source)](#EmfPlusBeginContainerNoParams_source_1) | 初始化一个新的 [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| stack_index | int | r/w | 获取或设置一个 32 位无符号整数，用于指定与<br/>图形状态容器关联的索引。该索引必须在后续的<br/>EmfPlusEndContainer 记录（第 2.3.7.3 节）中被引用，以关闭图形状态容器。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusBeginContainerNoParams(source) {#EmfPlusBeginContainerNoParams_source_1}


```
 EmfPlusBeginContainerNoParams(source) 
```

初始化一个新的 [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

