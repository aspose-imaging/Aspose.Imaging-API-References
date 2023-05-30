---
title: EmfPlusDrawLines Class
type: docs
weight: 150
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPlusDrawLines type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawLines(source)|Initializes a new instance of the EmfPlusDrawLines class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the lines. The value MUST be zero to 63, inclusive.|
|compressed|Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. <br/>            If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates<br/>            Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored|
|relative|Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is relative.<br/>            This bit indicates whether the PointData field specifies relative or absolute locations.<br/>            If set, each element in PointData specifies a location in the coordinate space that is relative <br/>            to the location specified by the previous element in the array. In the case of the first <br/>            element in PointData, a previous location at coordinates (0,0) is assumed. If clear, <br/>            PointData specifies absolute locations according to the C flag.<br/>            Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored|
|closed_shape|Gets or sets a value indicating whether [closed shape].|
|point_data|Gets or sets the point data<br/>            An array of Count points that specify the starting and ending points of the lines to be drawn.|
