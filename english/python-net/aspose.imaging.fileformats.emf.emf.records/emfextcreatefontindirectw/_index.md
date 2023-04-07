---
title: EmfExtCreateFontIndirectW Class
type: docs
weight: 410
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---

The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreateFontIndirectW

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfExtCreateFontIndirectW type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfExtCreateFontIndirectW(source)|Initializes a new instance of the EmfExtCreateFontIndirectW class|
|EmfExtCreateFontIndirectW()|Initializes a new instance of the [EmfExtCreateFontIndirectW](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|ih_fonts|Gets or sets a 32-bit unsigned integer that specifies the index of the logical font object<br/>            in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be<br/>            reused or modified.|
|elw|Gets or sets a LogFontExDv object (section 2.2.15), which specifies the logical font. A<br/>            LogFont object 2.2.13 MAY be present instead.[90]The process for determining the type of<br/>            object in this field is described below.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
