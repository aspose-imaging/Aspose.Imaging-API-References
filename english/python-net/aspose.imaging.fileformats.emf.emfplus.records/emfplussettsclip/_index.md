---
title: EmfPlusSetTsClip Class
type: docs
weight: 570
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---

The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsClip

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusSetTsClip type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusSetTsClip(source)|Initializes a new instance of the EmfPlusSetTsClip class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|compressed|Gets a value indicating whether this [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) is compressed.<br/>            This bit specifies the format of the rectangle data in the rects field. If set, each<br/>            rectangle is defined in 4 bytes. If clear, each rectangle is defined in 8 bytes.|
|num_rects|Gets the number rects.<br/>            This field specifies the number of rectangles that are defined in the rect field.|
|rects|Gets or sets an array of NumRects rectangles that define clipping areas. The format of<br/>            this data is determined by the C bit in the Flags field.|
