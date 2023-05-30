---
title: EmfRestoreDc Class
type: docs
weight: 970
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---

The EMR_RESTOREDC record restores the playback device context to the specified state. The<br/>            playback device context is restored by popping state information off a stack that was created by<br/>            prior EMR_SAVEDC records (section 2.3.11).

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfRestoreDc

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfRestoreDc type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfRestoreDc(source)|Initializes a new instance of the EmfRestoreDc class|
|EmfRestoreDc()|Initializes a new instance of the [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|saved_dc|Gets or sets a 32-bit signed integer that specifies the saved state to restore relative to<br/>            the current state. This value MUST be negative; –1 represents the state that was most<br/>            recently saved on the stack, –2 the one before that, etc.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
