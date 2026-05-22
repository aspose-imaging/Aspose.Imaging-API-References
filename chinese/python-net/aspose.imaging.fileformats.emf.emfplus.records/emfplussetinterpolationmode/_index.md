---
title: "EmfPlusSetInterpolationMode 类"
type: docs
weight: 510
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---

**Summary:** The EmfPlusSetInterpolationMode record specifies how image scaling, including stretching and shrinking, is performed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetInterpolationMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetInterpolationMode(source)](#EmfPlusSetInterpolationMode_source_1) | 初始化一个新的 [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| interpolation_mode | [EmfPlusInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/) | r/w | 获取或设置插值模式值，来自 InterpolationMode 枚举（第 2.1.1.16 节）。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetInterpolationMode(source) {#EmfPlusSetInterpolationMode_source_1}


```
 EmfPlusSetInterpolationMode(source) 
```

初始化一个新的 [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

