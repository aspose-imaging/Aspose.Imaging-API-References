---
title: EmfPlusSetClipRegion Class
type: docs
weight: 480
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---

The EmfPlusSetClipRegion record combines the current clipping region with another graphics region.<br/>            The new current clipping region is set to the result of performing the CombineMode operation on<br/>            the previous current clipping region and the specified EmfPlusRegion object.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRegion

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusSetClipRegion type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusSetClipRegion(source)|Initializes a new instance of the EmfPlusSetClipRegion class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|cm|Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. See the<br/>            CombineMode enumeration (section 2.1.1.4) for the meanings of the values.|
|object_id|Gets or sets the index of an EmfPlusRegion object (section 2.2.1.8) in the EMF+<br/>            Object Table.The value MUST be zero to 63, inclusive.|
