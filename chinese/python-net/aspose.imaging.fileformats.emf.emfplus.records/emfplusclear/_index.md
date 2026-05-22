---
title: "EmfPlusClear 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---

**Summary:** The EmfPlusClear record clears the output coordinate space and initializes it with a background color and transparency

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClear

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusClear(source)](#EmfPlusClear_source_1) | 初始化 [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | 获取或设置颜色。<br/>            一个定义屏幕绘制颜色的 EmfPlusARGB 对象（第 2.2.2.1 节）。所有颜色均采用 [IEC-RGB] 指定，除非另有说明。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusClear(source) {#EmfPlusClear_source_1}


```
 EmfPlusClear(source) 
```

初始化 [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

