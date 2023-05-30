---
title: EmfBeginPath Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---

This record opens a path bracket in the current playback device context.<br/>            After a path bracket is open, an application can begin processing records to define<br/>            the points that lie in the path.An application MUST close an open path bracket by<br/>            processing the EMR_ENDPATH record.<br/>            When an application processes the EMR_BEGINPATH record, all previous paths<br/>            MUST be discarded from the playback device context.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfBeginPath

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfBeginPath type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfBeginPath()|Initializes a new instance of the [EmfBeginPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
