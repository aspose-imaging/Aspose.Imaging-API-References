---
title: EmfExtCreatePen Class
type: docs
weight: 420
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---

The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An<br/>            optional DIB can be specified to use as the line style.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreatePen

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfExtCreatePen type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfExtCreatePen(record)|Initializes a new instance of the EmfExtCreatePen class|
|EmfExtCreatePen()|Initializes a new instance of the [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|ih_pen|Gets or sets  32-bit unsigned integer that specifies the index of the extended logical <br/>            pen object in the EMF Object Table (section 3.1.1.1). <br/>            This index MUST be saved so that this object can be reused or modified.|
|elp|Gets or sets a LogPenEx object (section 2.2.20) that specifies an extended logical <br/>            pen with attributes including an optional line style array.|
|bitmap_buffer|Gets or sets an optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object<br/>            ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR_EXTCREATEPEN record|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
