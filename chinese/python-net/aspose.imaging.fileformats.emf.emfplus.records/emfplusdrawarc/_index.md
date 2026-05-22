---
title: "EmfPlusDrawArc 类"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | 初始化一个新的 [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置数据的大小。<br/>            一个 32 位无符号整数，指定随后记录特定数据的 32 位对齐字节数。<br/>            对于此记录类型，值必须是以下之一：<br/>            0x00000010 如果 Flags 字段中的 C 位被设置。<br/>            0x00000018 如果 Flags 字段中的 C 位被清除。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            用于绘制弧线的 EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| rect_float | bool | r/w | 获取或设置一个值，以指示数据是否包含 <br/>            EmfPlusRectF 或 EmfPlusRect 记录<br/>            此位指示 RectData 字段中的数据是否已压缩。<br/>            如果设置，则 RectData 包含一个 EmfPlusRect 对象（第 2.2.2.38 节）。<br/>            如果清除，则 RectData 包含一个 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置矩形数据<br/>            可以是定义与弧线共线椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。该矩形定义了弧线的位置、大小和形状。此字段中对象的类型由 Flags 字段的值指定。 |
| size | int | r/w | 获取或设置大小。<br/>            一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。对于此记录类型，值必须是以下之一：<br/>            0x0000001C  如果 Flags 字段中的 C 位被设置。<br/>            0x00000024  如果 Flags 字段中的 C 位被清除。 |
| start_angle | float | r/w | 获取或设置起始角度<br/>            一个 32 位非负浮点值，指定 x 轴与弧线起始点之间的角度。任何值均可接受，但必须对 360 取模，使用的结果应在 0.0（含）到 360.0（不含）之间。 |
| sweep_angle | float | r/w | 获取或设置扫掠角度<br/>            一个 32 位浮点值，指定要绘制的弧线范围，以度数表示，从 StartAngle 值定义的起始点测量。任何值均可接受，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

初始化一个新的 [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

