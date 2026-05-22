---
title: "EmfPlusDrawString 类"
type: docs
weight: 190
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | 初始化一个新的 [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_id | int | r/w | 获取或设置画笔标识符<br/> 一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。此定义用于<br/> 绘制前景文本颜色；即仅绘制字形本身。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| format_id | int | r/w | 获取或设置格式标识符<br/> 一个 32 位无符号整数，指定 EMF+ 对象表中可选的 EmfPlusStringFormat 对象（第 2.2.1.9 节）的索引。<br/> 此对象指定要应用于字符串的文本布局信息和显示操作。 |
| is_color | bool | r/w | 获取或设置一个值，指示此实例是否为颜色。<br/> 如果设置，则 BrushId 以 EmfPlusARGB 对象（第 2.2.2.1 节）的形式指定颜色。<br/> 如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置布局矩形<br/> 一个 EmfPlusRectF 对象（第 2.2.2.39 节），定义将接收字符串的目标的边界区域。 |
| length | int | r/w | 获取或设置长度<br/> 一个 32 位无符号整数，指定字符串中的字符数。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/> EMF+ 对象表中 EmfPlusFont 对象（第 2.2.1.3 节）的索引，用于渲染文本。该值必须在 0 到 63（含）之间。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| string_data | string | r/w | 获取或设置字符串数据<br/> 一个 16 位 Unicode 字符数组，指定要绘制的字符串。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

初始化一个新的 [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

