---
title: "EmfPlusDrawPie 类"
type: docs
weight: 170
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---

**Summary:** The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawPie(source)](#EmfPlusDrawPie_source_1) | 初始化一个新的 [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 已压缩 | bool | r/w | 获取或设置一个值，指示 PointData 是否已压缩。<br/>            如果设置，RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。<br/>            如果未设置，RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            用于绘制饼图的 EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置矩形数据<br/>            可以是定义包含饼形楔形的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。此矩形定义了饼形的定位、大小<br/>            和形状。此字段中对象的类型由 Flags 字段的值指定。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| start_angle | float | r/w | 获取或设置起始角度<br/>            一个 32 位非负浮点值，指定 x 轴与饼形楔形起始点之间的角度。任何值均可接受，但必须对 360 取模解释，使用的结果在 0.0（含）到 360.0（不含）的范围内。 |
| sweep_angle | float | r/w | 获取或设置扫掠角度<br/>            一个 32 位浮点值，指定从 StartAngle 值定义的起始点测量的弧度范围，以度数表示，用于绘制饼形楔形。任何值均可接受，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawPie(source) {#EmfPlusDrawPie_source_1}


```
 EmfPlusDrawPie(source) 
```

初始化一个新的 [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

