---
title: "EmfPlusEndContainer 类"
type: docs
weight: 210
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---

**Summary:** The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusEndContainer(source)](#EmfPlusEndContainer_source_1) | 初始化 [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| stack_index | int | r/w | 获取或设置一个 32 位无符号整数，指定图形状态容器的索引<br/>            该索引必须匹配先前 EmfPlusBeginContainer（第 2.3.7.1 节）或<br/>            EmfPlusBeginContainerNoParams 记录（第 2.3.7.2 节）打开的图形状态容器关联的值。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusEndContainer(source) {#EmfPlusEndContainer_source_1}


```
 EmfPlusEndContainer(source) 
```

初始化 [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

