---
title: EmfCloseFigure Class
type: docs
weight: 120
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---

This record closes an open figure in a path.<br/>            Processing the EMR_CLOSEFIGURE record MUST close the figure by drawing a line<br/>            from the current position to the first point of the figure, and then it MUST connect<br/>            the lines by using the line join style.If a figure is closed by processing the<br/>            EMR_LINETO record instead of the EMR_CLOSEFIGURE record, end caps are<br/>            used to create the corner instead of a join.EMR_LINETO is specified in section<br/>            2.3.5.13.<br/>            The EMR_CLOSEFIGURE record SHOULD only be used if there is an open path<br/>            bracket in the playback device context.<br/>            A figure in a path is open unless it is explicitly closed by processing this record.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCloseFigure

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfCloseFigure type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCloseFigure()|Initializes a new instance of the [EmfCloseFigure](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/) class.|
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
