---
title: "EmfPlusDrawImage 类"
type: docs
weight: 130
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | 初始化一个新的 [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 已压缩 | bool | r/w | 获取或设置一个值，指示 PointData 是否已压缩。<br/>            如果设置，RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。<br/>            如果未设置，RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| image_attributes_id | int | r/w | 获取或设置图像属性标识符<br/>            一个 32 位无符号整数，指定 EMF+ 对象表中可选的 EmfPlusImageAttributes 对象（第 2.2.1.5 节）的索引。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            EMF+ 对象表中 EmfPlusImage 对象（第 2.2.1.4 节）的索引，指定要渲染的图像。该值必须在 0 到 63（含）之间。 |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置矩形数据<br/>            可以是 EmfPlusRect 或 EmfPlusRectF 对象，定义图像的边界框。<br/>            由 SrcRect 字段指定的图像部分将被缩放以适应此矩形。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置源矩形<br/>            一个 EmfPlusRectF 对象，指定要渲染的图像部分。<br/>            由此矩形指定的图像部分将被缩放以适应由 RectData 字段指定的目标矩形。 |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | 获取或设置源单位<br/>            32 位有符号整数，指定 SrcRect 字段的单位。<br/>            必须是 UnitType 枚举（第 2.1.1.33 节）中的 UnitTypePixel 成员。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

初始化一个新的 [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

