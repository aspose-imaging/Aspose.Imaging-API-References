---
title: "EmfPlusRotateWorldTransform 类"
type: docs
weight: 410
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---

**Summary:** The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRotateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusRotateWorldTransform(source)](#EmfPlusRotateWorldTransform_source_1) | 初始化 [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 角度 | float | r/w | 获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。<br/>            该操作通过构建以下矩阵来执行<br/>            ---------------------------------<br/> | sin(Angle) | cos(Angle) | 0 | <br/> | cos(Angle) | sin(Angle) | 0 | <br/>            ---------------------------------<br/>            图 2：旋转变换矩阵<br/>            当前世界空间变换与此矩阵相乘，结果成为新的当前世界空间变换。Flags 字段决定乘法的顺序。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| post_multiplied_matrix | bool | r | 获取一个值，指示是否为 [post multiplied matrix]。<br/>            如果设置，则变换矩阵应后乘。如果未设置，则应前乘。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusRotateWorldTransform(source) {#EmfPlusRotateWorldTransform_source_1}


```
 EmfPlusRotateWorldTransform(source) 
```

初始化 [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

