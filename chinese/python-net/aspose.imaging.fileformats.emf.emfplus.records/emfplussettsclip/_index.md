---
title: "EmfPlusSetTsClip 类"
type: docs
weight: 570
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---

**Summary:** The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsClip

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetTsClip(source)](#EmfPlusSetTsClip_source_1) | 初始化一个新的 [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| compressed | bool | r | 获取一个值，指示此 [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) 是否已压缩。<br/> 此位指定 rects 字段中矩形数据的格式。如果设置，则每个矩形以 4 字节定义；如果未设置，则每个矩形以 8 字节定义。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| num_rects | int | r | 获取矩形数量。<br/> 此字段指定在 rect 字段中定义的矩形数量。 |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 NumRects 矩形数组，用于定义裁剪区域。此数据的格式由 Flags 字段中的 C 位决定。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetTsClip(source) {#EmfPlusSetTsClip_source_1}


```
 EmfPlusSetTsClip(source) 
```

初始化一个新的 [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

