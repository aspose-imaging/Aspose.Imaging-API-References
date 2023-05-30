---
title: EmfSelectObject Class
type: docs
weight: 1040
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---

The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device<br/>            context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its<br/>            value from the StockObject enumeration(section 2.1.31).

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectObject

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfSelectObject type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfSelectObject(record)|Initializes a new instance of the EmfSelectObject class|
|EmfSelectObject()|Initializes a new instance of the [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|Gets or sets the type.|
|size|Gets or sets the size of the record|
|object_handle|Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object <br/>            in the EMF Object Table or the index of a stock object from the [EmfStockObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/) enumeration.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.|
|create_from_type(type)|Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.|
