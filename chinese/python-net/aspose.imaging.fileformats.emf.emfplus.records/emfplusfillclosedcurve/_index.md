---
title: "EmfPlusFillClosedCurve 类"
type: docs
weight: 230
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | 初始化 [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_id | int | r/w | 获取或设置画笔标识符<br/>            一个 32 位无符号整数，指定 EmfPlusBrush，其内容由 Flags 字段中的 S 位决定。此画笔用于填充闭合基数样条的内部。 |
| compressed | bool | r/w | 获取或设置一个值，指示此 [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) 是否压缩。<br/>            此位指示 PointData 字段是否指定压缩数据。<br/>            如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。<br/>            如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。<br/>            ----------------------<br/>            “winding” 填充操作根据 “even-odd parity” 规则填充区域。<br/>            根据该规则，可以通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点向远离曲线的点画一条直线。如果该直线与曲线相交的次数为奇数，则测试点在曲线内部；否则在曲线外部。<br/>            ---------------------<br/>            “alternate” 填充操作根据 “non-zero” 规则填充区域。<br/>            根据该规则，可以通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点向远离曲线的点画一条直线。统计曲线从左向右穿过测试线的次数，以及从右向左穿过的次数。如果这两个数字相同，测试点在曲线外部；否则在曲线内部。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| is_color | bool | r/w | 获取或设置一个值，指示此实例是否为颜色。<br/> 如果设置，则 BrushId 以 EmfPlusARGB 对象（第 2.2.2.1 节）的形式指定颜色。<br/> 如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置点数据<br/>            一个包含 Count 个点的数组，指定定义样条的线段的端点。<br/>            在闭合基数样条中，曲线会通过 PointData 数组中的最后一个点并与数组中的第一个点相连。 |
| relative | bool | r/w | 获取或设置一个值，指示此 [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) 是否相对。<br/>            此位指示 PointData 字段是指定相对位置还是绝对位置。<br/>            如果设置，PointData 中的每个元素指定坐标空间中的一个位置，<br/>            该位置相对于数组中前一个元素指定的位置。对于第一个元素，假定前一个位置的坐标为 (0,0)。<br/>            如果未设置，PointData 根据 C 标志指定绝对位置。<br/>            注意：如果此标志被设置，上述 C 标志未定义，必须忽略。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| 张力 | float | r/w | 获取或设置张力<br/>            一个 32 位浮点值，指定样条在通过各点时的弯曲程度。值为 0.0 表示样条是一系列直线。值越大，曲线越圆润。更多信息，请参见 [SPLINE77] 和 [PETZOLD]。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |
| winding | bool | r/w | 获取或设置一个值，指示此 [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) 是否为 winding（环绕）。<br/>            此位指示填充操作的方式。<br/>            如果设置，填充为 “winding” 填充；如果未设置，填充为 “alternate” 填充。 |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

初始化 [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

