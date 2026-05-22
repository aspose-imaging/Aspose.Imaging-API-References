---
title: "EmfPlusDrawImagePoints 类"
type: docs
weight: 140
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | 初始化一个新的 [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | 获取或设置一个值，以指示是否 [applying an effect]。<br/>            此位指示图像的渲染是否包括应用效果。<br/>            如果设置，则必须在之前的 EmfPlusSerializableObject 记录（第 2.3.5.2 节）中指定 Effect 类的对象。 |
| 已压缩 | bool | r/w | 获取或设置一个值，以指示 PointData 是否已压缩。<br/>            此位指示 PointData 字段是否指定压缩数据。<br/>            如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。<br/>            如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。<br/>            注意：如果下面的 P 标志被设置，则此标志未定义，必须被忽略。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| image_attributes_id | int | r/w | 获取或设置一个 32 位无符号整数，包含 EMF+ 对象表中可选 EmfPlusImageAttributes 对象（第 2.2.1.5 节）的索引。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            EMF+ 对象表中 EmfPlusImage 对象（第 2.2.1.4 节）的索引，指定要渲染的图像。该值必须在 0 到 63（含）之间。 |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置一个 Count 点数组，指定平行四边形的三个点。<br/>            这三个点分别代表平行四边形的左上、右上和左下角。第四个点由前三个点外推得到。<br/>            SrcRect 字段指定的图像部分如果需要，应当应用缩放和剪切变换，以适应平行四边形内部。 |
| relative | bool | r/w | 获取或设置一个值，以指示此 [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) 是否为相对坐标。<br/>            此位指示 PointData 字段是指定相对位置还是绝对位置。<br/>            如果设置，PointData 中的每个元素指定相对于数组中前一个元素位置的坐标。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。<br/>            如果未设置，PointData 根据 C 标志指定绝对位置。<br/>            注意：如果设置此标志，上面的 C 标志未定义，必须被忽略。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），定义要渲染的图像部分。 |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | 获取或设置一个 32 位有符号整数，定义 SrcRect 字段的单位。它必须是 UnitType 枚举（第 2.1.1.33 节）中的 UnitPixel 值。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

初始化一个新的 [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

