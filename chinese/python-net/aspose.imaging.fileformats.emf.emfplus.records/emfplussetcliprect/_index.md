---
title: "EmfPlusSetClipRect 类"
type: docs
weight: 470
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---

**Summary:** The EmfPlusSetClipRect record combines the current clipping region with a rectangle.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRect

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetClipRect(source)](#EmfPlusSetClipRect_source_1) | 初始化 [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| clip_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），用于定义在 CombineMode 操作中使用的矩形。 |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | 获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。请参阅<br/>            CombineMode 枚举（第 2.1.1.4 节）以了解各取值的含义。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSetClipRect(source) {#EmfPlusSetClipRect_source_1}


```
 EmfPlusSetClipRect(source) 
```

初始化 [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

