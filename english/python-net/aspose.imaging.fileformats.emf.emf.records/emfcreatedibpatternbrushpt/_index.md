---
title: EmfCreateDibPatternBrushPt Class
type: docs
weight: 280
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---

The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The<br/>            pattern is specified by a DIB.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateDibPatternBrushPt

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfCreateDibPatternBrushPt type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCreateDibPatternBrushPt(source)|Initializes a new instance of the EmfCreateDibPatternBrushPt class|
|EmfCreateDibPatternBrushPt()|Initializes a new instance of the [EmfCreateDibPatternBrushPt](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|ih_brush|Gets or sets a 32-bit unsigned integer that specifies the index of the pattern brush<br/>            object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object<br/>            can be reused or modified.|
|usage|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color<br/>            table in the DIB header. This value MUST be in the DIBColors enumeration (section 2.1.9).|
|bitmap_buffer|Gets or sets a buffer containing a packed DIB in the form of a WMF<br/>            DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be<br/>            contiguous with the fixed portion of the EMR_CREATEDIBPATTERNBRUSHPT record.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
