---
title: EmfCreatePalette Class
type: docs
weight: 300
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---

The EMR_CREATEPALETTE record defines a logical palette for graphics operations.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePalette

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfCreatePalette type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCreatePalette(source)|Initializes a new instance of the EmfCreatePalette class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|ih_pal|Gets or sets a 32-bit unsigned integer that specifies the index of the logical palette object<br/>            in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be<br/>            reused or modified.|
|log_palette|Gets or sets a LogPalette object (section 2.2.17). The Version field of this object<br/>            MUST be set to 0x0300. If the NumberOfEntries value in this object is zero, processing of<br/>            this record MUST fail.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
