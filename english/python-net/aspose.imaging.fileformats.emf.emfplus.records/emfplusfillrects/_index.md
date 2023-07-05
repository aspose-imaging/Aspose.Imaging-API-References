---
title: EmfPlusFillRects Class
type: docs
weight: 280
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---

The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRects

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusFillRects type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusFillRects(source)|Initializes a new instance of the EmfPlusFillRects class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1).<br/>            If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table|
|compressed|Gets or sets a value indicating whether this [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData<br/>             contains an EmfPlusRectF object (section 2.2.2.39) object|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field.|
|rect_data|Gets or sets the rectangle data<br/>            An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data.|
