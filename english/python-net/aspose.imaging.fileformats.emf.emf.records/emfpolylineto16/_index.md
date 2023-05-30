---
title: EmfPolylineTo16 Class
type: docs
weight: 920
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---

The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position. <br/>            A line is drawn from the current position to the first point specified by the aPoints field by using the <br/>            current pen. For each additional line, drawing is performed from the ending point of the previous <br/>            line to the next point specified by aPoints.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolylineTo16

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPolylineTo16 type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPolylineTo16(source)|Initializes a new instance of the EmfPolylineTo16 class|
|EmfPolylineTo16()|Initializes a new instance of the [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, <br/>            which specifies the bounding rectangle, in device units.|
|a_points|Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] <br/>            section 2.2.2.16, which specifies the array of points.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
