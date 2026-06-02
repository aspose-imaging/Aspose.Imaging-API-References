---
title: "EmfPlusScaleWorldTransform 类"
type: docs
weight: 430
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---

**Summary:** The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusScaleWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusScaleWorldTransform(source)](#EmfPlusScaleWorldTransform_source_1) | 初始化 [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| post_multiplied_matrix | bool | r | 获取一个值，指示是否为 [post multiplied matrix]。<br/>            若设置，变换矩阵应后乘；若未设置，应前乘。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| sx | float | r/w | 获取或设置定义水平缩放因子的 32 位浮点值。缩放<br/>            通过使用 Sx 和 Sy 字段值构建新的变换矩阵来执行，如下表所示。<br/>            -----------------<br/> | Sx | 0 | 0 | <br/> | 0 | Sx | 0 | <br/>            -----------------<br/>            图 3：缩放变换矩阵 |
| sy | float | r/w | 获取或设置定义垂直缩放因子的 32 位浮点值。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusScaleWorldTransform(source) {#EmfPlusScaleWorldTransform_source_1}


```
 EmfPlusScaleWorldTransform(source) 
```

初始化 [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

