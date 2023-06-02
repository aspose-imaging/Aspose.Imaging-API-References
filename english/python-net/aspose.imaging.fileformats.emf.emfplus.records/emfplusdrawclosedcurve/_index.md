---
title: EmfPlusDrawClosedCurve Class
type: docs
weight: 90
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusDrawClosedCurve type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawClosedCurve(source)|Initializes a new instance of the EmfPlusDrawClosedCurve class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the closed curve. The value MUST be zero to 63, inclusive.|
|compressed|Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. <br/>            If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates<br/>            Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored|
|relative|Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is relative.<br/>            This bit indicates whether the PointData field specifies relative or absolute locations.<br/>            If set, each element in PointData specifies a location in the coordinate space that is relative <br/>            to the location specified by the previous element in the array. In the case of the first <br/>            element in PointData, a previous location at coordinates (0,0) is assumed. If clear, <br/>            PointData specifies absolute locations according to the C flag.<br/>            Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored|
|tension|Gets or sets the tension<br/>            A 32-bit floating point number that specifies how tightly the spline <br/>            bends as it passes through the points. A value of 0 specifies that <br/>            the spline is a sequence of straight lines. As the value increases, <br/>            the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD].|
|point_data|Gets or sets the point data<br/>            An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, <br/>            the curve continues through the last point in the PointData array and connects with the first point in the array.<br/>            The type of data in this array is specified by the Flags field, as follows: Data Type Meaning<br/>            EmfPlusPointR object (section 2.2.2.37)<br/>            If the P flag is set in the Flags, the points specify relative locations.<br/>            EmfPlusPointF object (section 2.2.2.36)<br/>            If the P and C bits are set in the Flags field, the points specify absolute locations.<br/>            EmfPlusPoint object (section 2.2.2.35)<br/>            If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations.|
