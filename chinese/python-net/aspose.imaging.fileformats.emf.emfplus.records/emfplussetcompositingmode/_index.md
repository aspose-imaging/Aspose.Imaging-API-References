---
title: "EmfPlusSetCompositingMode 类"
type: docs
weight: 490
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---

**Summary:** The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetCompositingMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetCompositingMode(source)](#EmfPlusSetCompositingMode_source_1) | 初始化一个新的 [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | 获取或设置合成模式值，来自 CompositingMode<br/>            枚举（第 2.1.1.5 节）。合成可以表示为 alpha 混合的状态，状态可以是开启或关闭。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetCompositingMode(source) {#EmfPlusSetCompositingMode_source_1}


```
 EmfPlusSetCompositingMode(source) 
```

初始化一个新的 [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

