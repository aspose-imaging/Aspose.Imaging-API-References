---
title: EmfRecord Class
type: docs
weight: 940
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/
---

Base class for EMF records<br/>            All EMF records MUST have a length that is a multiple of 4 bytes. This is depicted in the<br/>            generic structures of the preceding EMF record types by including AlignmentPadding fields<br/>            where appropriate at the ends of these structures. The contents of AlignmentPadding fields<br/>            MUST always be ignored. For brevity, these fields are not shown in every individual EMF<br/>            record definition.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfRecord

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfRecord type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfRecord()|Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.|
|EmfRecord(source)|Initializes a new instance of the EmfRecord class|
|EmfRecord(type)|Initializes a new instance of the EmfRecord class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|Gets or sets the type.|
|size|Gets or sets the size of the record|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.|
|create_from_type(type)|Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.|
