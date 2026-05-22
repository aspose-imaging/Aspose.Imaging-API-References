---
title: "EmfPlusSetWorldTransform 类"
type: docs
weight: 590
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---

**Summary:** The EmfPlusSetWorldTransform record sets the world transform according to the values in a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetWorldTransform(source)](#EmfPlusSetWorldTransform_source_1) | 初始化一个新的 [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），它定义了<br/> 新的当前世界变换。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetWorldTransform(source) {#EmfPlusSetWorldTransform_source_1}


```
 EmfPlusSetWorldTransform(source) 
```

初始化一个新的 [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

