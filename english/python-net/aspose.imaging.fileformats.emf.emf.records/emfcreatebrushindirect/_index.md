---
title: EmfCreateBrushIndirect Class
type: docs
weight: 250
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---

The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateBrushIndirect

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfCreateBrushIndirect type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCreateBrushIndirect(source)|Initializes a new instance of the EmfCreateBrushIndirect class|
|EmfCreateBrushIndirect()|Initializes a new instance of the [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|ih_brush|Gets or sets A 32-bit unsigned integer that specifies the index of the logical brush object<br/>            in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be<br/>            reused or modified.|
|log_brush|Gets or sets A LogBrushEx object (section 2.2.12) that specifies the style, color, and<br/>            pattern of the logical brush. The BrushStyle field in this object MUST be BS_SOLID,<br/>            BS_HATCHED, or BS_NULL.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
