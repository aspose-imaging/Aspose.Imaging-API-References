---
title: EmfCreateMonoBrush Class
type: docs
weight: 290
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---

The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations.<br/>            The pattern is specified by a monochrome DIB.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateMonoBrush

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfCreateMonoBrush type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCreateMonoBrush(source)|Initializes a new instance of the EmfCreateMonoBrush class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|ih_brush|Gets or sets a 32-bit unsigned integer that specifies the index of the monochrome<br/>            pattern brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so<br/>            that this object can be reused or modified.|
|usage|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color<br/>            table in the DIB header. This value MUST be in the DIBColors enumeration (section 2.1.9).|
|bitmap_buffer|Gets or sets a buffer containing a packed DIB in the form of a WMF<br/>            DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be<br/>            contiguous with the fixed portion of the EMR_CREATEDIBPATTERNBRUSHPT record.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
