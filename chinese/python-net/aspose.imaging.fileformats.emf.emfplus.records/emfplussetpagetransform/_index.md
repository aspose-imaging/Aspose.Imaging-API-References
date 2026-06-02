---
title: "EmfPlusSetPageTransform 类"
type: docs
weight: 520
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---

**Summary:** The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space<br/>            coordinates to device space coordinates.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPageTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetPageTransform(source)](#EmfPlusSetPageTransform_source_1) | 初始化 [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| page_scale | float | r/w | 获取或设置一个 32 位浮点值，用于指定将页面空间坐标转换为设备空间坐标的比例因子。<br/>             |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | 获取页面空间坐标的计量单位，来自 UnitType<br/>            枚举（第 2.1.1.33 节）。此值不应为 UnitTypeDisplay 或 UnitTypeWorld。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetPageTransform(source) {#EmfPlusSetPageTransform_source_1}


```
 EmfPlusSetPageTransform(source) 
```

初始化 [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

