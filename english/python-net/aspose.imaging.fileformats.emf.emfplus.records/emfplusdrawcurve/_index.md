---
title: EmfPlusDrawCurve Class
type: docs
weight: 100
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusDrawCurve type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawCurve(source)|Initializes a new instance of the EmfPlusDrawCurve class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|compressed|Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. <br/>            If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates<br/>            Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored|
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the curve. The value MUST be zero to 63, inclusive.|
|tension|Gets or sets the tension<br/>            A 32-bit floating point number that specifies how tightly the spline <br/>            bends as it passes through the points. A value of 0 specifies that <br/>            the spline is a sequence of straight lines. As the value increases, <br/>            the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD].|
|num_segments|Gets or sets the segments count <br/>            A 32-bit unsigned integer that specifies the number of line segments making up the spline.|
|point_data|Gets or sets an array of either 32-bit signed integers or 32-bit floating-point numbers of <br/>            Count length that defines coordinate values of the endpoints of the lines to be stroked.|
