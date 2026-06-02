---
title: "EmfPlusSetAntiAliasMode 类"
type: docs
weight: 450
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---

**Summary:** The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetAntiAliasMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetAntiAliasMode(source)](#EmfPlusSetAntiAliasMode_source_1) | 初始化 [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| anti_aliasing | bool | r/w | 获取或设置一个值，指示是否为 [anti aliasing]。<br/>            如果设置，则应执行抗锯齿。<br/>            如果未设置，则不应执行抗锯齿。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| smoothing_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | 获取或设置平滑模式。<br/>            (7 位)：平滑模式值，来自 SmoothingMode 枚举（第 2.1.1.28 节） |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetAntiAliasMode(source) {#EmfPlusSetAntiAliasMode_source_1}


```
 EmfPlusSetAntiAliasMode(source) 
```

初始化 [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

