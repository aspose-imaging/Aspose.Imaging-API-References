---
title: EmfPlusFillPolygon Class
type: docs
weight: 270
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusFillPolygon type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusFillPolygon(source)|Initializes a new instance of the EmfPlusFillPolygon class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). <br/>            If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.|
|is_compressed|Gets or sets a value indicating whether this instance is compressed.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit <br/>            integer coordinates. If clear, PointData specifies absolute locations in the coordinate <br/>            space with 32-bit floating-point coordinates|
|is_relative|Gets or sets a value indicating whether this instance is relative.<br/>            If set, each element in PointData specifies a location in the coordinate <br/>            space that is relative to the location specified by the previous element <br/>            in the array. In the case of the first element in PointData, a previous <br/>            location at coordinates (0,0) is assumed. If clear, PointData specifies <br/>            absolute locations according to the C flag|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that defines the brush, the content <br/>            of which is determined by the S bit in the Flags field.|
|point_data|Gets or sets the point data<br/>            An array of Count points that define the vertices of the polygon. <br/>            The first two points in the array specify the first side of the polygon. <br/>            Each additional point specifies a new side, the vertices of which <br/>            include the point and the previous point. If the last point and the <br/>            first point do not coincide, they specify the last side of the polygon.|
