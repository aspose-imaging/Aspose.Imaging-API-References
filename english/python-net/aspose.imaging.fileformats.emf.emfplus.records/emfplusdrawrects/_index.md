---
title: EmfPlusDrawRects Class
type: docs
weight: 180
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---

The EmfPlusDrawRects record specifies drawing a series of rectangles

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawRects

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusDrawRects type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawRects(source)|Initializes a new instance of the EmfPlusDrawRects class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|compressed|Gets or sets a value indicating whether the PointData is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38).<br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).|
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the rectangles. The value MUST be zero to 63, inclusive.|
|rect_data|Gets or sets the rect data<br/>            An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data.|
