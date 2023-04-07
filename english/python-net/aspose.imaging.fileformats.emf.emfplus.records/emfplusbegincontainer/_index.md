---
title: EmfPlusBeginContainer Class
type: docs
weight: 10
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---

The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainer

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusBeginContainer type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusBeginContainer(source)|Initializes a new instance of the EmfPlusBeginContainer class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|page_unit|Gets the page unit.|
|dest_rect|Gets or sets an EmfPlusRectF object (section 2.2.2.39) that, with SrcRect, specifies<br/>            a transform for the container. This transformation results in SrcRect when applied to DestRect.|
|src_rect|Gets or sets an EmfPlusRectF rectangle that, with DestRect, specifies a transformation<br/>            for the container. This transformation results in SrcRect when applied to DestRect.|
|stack_index|Gets or sets a 32-bit unsigned integer that specifies an index to associate with the<br/>            graphics state container. The index MUST be referenced by a subsequent<br/>            EmfPlusEndContainer record (section 2.3.7.3) to close the graphics state container.|
