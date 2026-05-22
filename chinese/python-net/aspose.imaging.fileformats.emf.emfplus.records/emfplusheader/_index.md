---
title: "EmfPlusHeader 类"
type: docs
weight: 310
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | 初始化一个新的 [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| dual_mode | bool | r/w | 获取或设置一个值，以指示是否为 [dual mode]。<br/>如果设置，则此标志表示该元文件为“dual-mode”，这意味着它包含两套记录，每套记录完整地指定<br/>图形内容。如果清除，则图形内容由 EMF+ <br/>记录指定，且可能由在 EmfPlusGetDC 记录之前的 EMF 记录指定。<br/>如果设置此标志，仅 EMF 记录应足以定义<br/>图形内容。请注意，无论“dual-mode”标志是否设置，某些<br/>EMF 记录始终存在，即 EMF 控制记录以及包含 EMF+ 记录的 EMF 记录。EMF 控制记录在 [MS-EMF] <br/>第 2.3.4 节中指定。 |
| emf_plus_flags | int | r/w | 获取或设置 EMF plus 标志。<br/>一个 32 位无符号整数，包含有关此元文件记录方式的信息。<br/>如果字段的第 31 位被设置，则此标志表示该元文件是使用视频显示的参考设备上下文记录的。<br/>如果清除，则该元文件是使用打印机的参考设备上下文记录的。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| is_valid | bool | r | 获取一个值，指示此实例是否有效。 |
| logical_dpi_x | int | r/w | 获取或设置逻辑 dpi x。<br/>一个 32 位无符号整数，指定记录此元文件时的水平分辨率，单位为每英寸像素数。 |
| logical_dpi_y | int | r/w | 获取或设置逻辑 dpi y。<br/>一个 32 位无符号整数，指定记录此元文件时的垂直分辨率，单位为每英寸线数。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | 获取或设置版本。<br/>一个 EmfPlusGraphicsVersion 对象（第 2.2.2.19 节），指定用于创建此元文件的操作系统图形版本。 |
| video_display | bool | r/w | 获取或设置一个值，以指示是否为视频显示。<br/>如果设置，则此标志表示该元文件是使用视频显示的参考设备上下文记录的。<br/>如果清除，则该元文件是使用打印机的参考设备上下文记录的。 |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

初始化一个新的 [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

