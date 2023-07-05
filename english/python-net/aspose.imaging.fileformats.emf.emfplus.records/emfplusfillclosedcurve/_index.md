---
title: EmfPlusFillClosedCurve Class
type: docs
weight: 230
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusFillClosedCurve type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusFillClosedCurve(source)|Initializes a new instance of the EmfPlusFillClosedCurve class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1).<br/>            If clear, BrushId contains the index of an EmfPlusBrush object <br/>            (section 2.2.1.1) in the EMF+ Object Table.|
|compressed|Gets or sets a value indicating whether this [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit <br/>            integer coordinates. If clear, PointData specifies absolute locations in the <br/>            coordinate space with 32-bit floating-point coordinates.<br/>            ----------------------<br/>            A "winding" fill operation fills areas according to the "even-odd parity" rule. <br/>            According to this rule, a test point can be determined to be inside or outside a <br/>            closed curve as follows: Draw a line from the test point to a point that is distant <br/>            from the curve. If that line crosses the curve an odd number of times, the test <br/>            point is inside the curve; otherwise, the test point is outside the curve.<br/>            ---------------------<br/>            An "alternate" fill operation fills areas according to the "non-zero" rule.<br/>             According to this rule, a test point can be determined to be inside or outside <br/>            a closed curve as follows: Draw a line from a test point to a point that is <br/>            distant from the curve. Count the number of times the curve crosses the test <br/>            line from left to right, and count the number of times the curve crosses the <br/>            test line from right to left. If those two numbers are the same, the test point <br/>            is outside the curve; otherwise, the test point is inside the curve.|
|winding|Gets or sets a value indicating whether this [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) is winding.<br/>            This bit indicates how to perform the fill operation.<br/>            If set, the fill is a "winding" fill. If clear, the fill is an "alternate" fill.|
|relative|Gets or sets a value indicating whether this [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) is relative.<br/>            This bit indicates whether the PointData field specifies relative or absolute locations.<br/>            If set, each element in PointData specifies a location in the coordinate space that is<br/>            relative to the location specified by the previous element in the array. In the case <br/>            of the first element in PointData, a previous location at coordinates (0,0) is assumed. <br/>            If clear, PointData specifies absolute locations according to the C flag.<br/>            Note If this flag is set, the C flag (above) is undefined and MUST be ignored.|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that specifies the EmfPlusBrush, the content of which is <br/>            determined by the S bit in the Flags field. This brush is used to fill the interior <br/>            of the closed cardinal spline.|
|tension|Gets or sets the tension<br/>            A 32-bit floating point value that specifies how tightly the spline bends as it passes <br/>            through the points. A value of 0.0 specifies that the spline is a sequence of straight <br/>            lines. As the value increases, the curve becomes more rounded. For more information, <br/>            see [SPLINE77] and [PETZOLD].|
|point_data|Gets or sets the point data<br/>            An array of Count points that specify the endpoints of the lines that define the spline. <br/>            In a closed cardinal spline, the curve continues through the last point in the PointData <br/>            array and connects with the first point in the array|
