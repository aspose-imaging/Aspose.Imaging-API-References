---
title: EmfPlusFillClosedCurve Class
type: docs
weight: 230
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Initializes a new instance of the [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that specifies the EmfPlusBrush, the content of which is <br/>            determined by the S bit in the Flags field. This brush is used to fill the interior <br/>            of the closed cardinal spline. |
| compressed | bool | r/w | Gets or sets a value indicating whether this [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit <br/>            integer coordinates. If clear, PointData specifies absolute locations in the <br/>            coordinate space with 32-bit floating-point coordinates.<br/>            ----------------------<br/>            A "winding" fill operation fills areas according to the "even-odd parity" rule. <br/>            According to this rule, a test point can be determined to be inside or outside a <br/>            closed curve as follows: Draw a line from the test point to a point that is distant <br/>            from the curve. If that line crosses the curve an odd number of times, the test <br/>            point is inside the curve; otherwise, the test point is outside the curve.<br/>            ---------------------<br/>            An "alternate" fill operation fills areas according to the "non-zero" rule.<br/>             According to this rule, a test point can be determined to be inside or outside <br/>            a closed curve as follows: Draw a line from a test point to a point that is <br/>            distant from the curve. Count the number of times the curve crosses the test <br/>            line from left to right, and count the number of times the curve crosses the <br/>            test line from right to left. If those two numbers are the same, the test point <br/>            is outside the curve; otherwise, the test point is inside the curve. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| is_color | bool | r/w | Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1).<br/>            If clear, BrushId contains the index of an EmfPlusBrush object <br/>            (section 2.2.1.1) in the EMF+ Object Table. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the point data<br/>            An array of Count points that specify the endpoints of the lines that define the spline. <br/>            In a closed cardinal spline, the curve continues through the last point in the PointData <br/>            array and connects with the first point in the array |
| relative | bool | r/w | Gets or sets a value indicating whether this [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) is relative.<br/>            This bit indicates whether the PointData field specifies relative or absolute locations.<br/>            If set, each element in PointData specifies a location in the coordinate space that is<br/>            relative to the location specified by the previous element in the array. In the case <br/>            of the first element in PointData, a previous location at coordinates (0,0) is assumed. <br/>            If clear, PointData specifies absolute locations according to the C flag.<br/>            Note If this flag is set, the C flag (above) is undefined and MUST be ignored. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| tension | float | r/w | Gets or sets the tension<br/>            A 32-bit floating point value that specifies how tightly the spline bends as it passes <br/>            through the points. A value of 0.0 specifies that the spline is a sequence of straight <br/>            lines. As the value increases, the curve becomes more rounded. For more information, <br/>            see [SPLINE77] and [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| winding | bool | r/w | Gets or sets a value indicating whether this [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) is winding.<br/>            This bit indicates how to perform the fill operation.<br/>            If set, the fill is a "winding" fill. If clear, the fill is an "alternate" fill. |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Initializes a new instance of the [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

