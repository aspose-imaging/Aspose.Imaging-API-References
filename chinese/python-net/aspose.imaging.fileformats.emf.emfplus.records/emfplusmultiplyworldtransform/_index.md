---
title: "EmfPlusMultiplyWorldTransform 类"
type: docs
weight: 320
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---

**Summary:** The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusMultiplyWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusMultiplyWorldTransform(source)](#EmfPlusMultiplyWorldTransform_source_1) | 初始化一个新的 [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），用于定义乘法矩阵。 |
| post_multiplied_matrix | bool | r | 获取一个值，指示是否为 [post multiplied matrix]。<br/>            若设置，变换矩阵应后乘；若未设置，应前乘。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusMultiplyWorldTransform(source) {#EmfPlusMultiplyWorldTransform_source_1}


```
 EmfPlusMultiplyWorldTransform(source) 
```

初始化一个新的 [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

