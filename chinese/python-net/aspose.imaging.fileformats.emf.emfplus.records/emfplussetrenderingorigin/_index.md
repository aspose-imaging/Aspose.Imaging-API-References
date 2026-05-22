---
title: "EmfPlusSetRenderingOrigin 类"
type: docs
weight: 540
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/
---

**Summary:** The EmfPlusSetRenderingOrigin record specifies the rendering origin for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetRenderingOrigin

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetRenderingOrigin(source)](#EmfPlusSetRenderingOrigin_source_1) | 初始化一个新的 [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |
| x | int | r/w | 获取或设置一个 32 位无符号整数，用于定义渲染原点的水平坐标值。 |
| y | int | r/w | 获取或设置一个 32 位无符号整数，用于定义渲染原点的垂直坐标值。 |


### Constructor: EmfPlusSetRenderingOrigin(source) {#EmfPlusSetRenderingOrigin_source_1}


```
 EmfPlusSetRenderingOrigin(source) 
```

初始化一个新的 [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

