---
title: EmfPlusFillRegion Class
type: docs
weight: 290
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---

The EmfPlusFillRegion record specifies filling the interior of a graphics region

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRegion

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusFillRegion type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusFillRegion(source)|Initializes a new instance of the EmfPlusFillRegion class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|object_id|Gets or sets the object identifier.<br/>            The index of the EmfPlusRegion object (section 2.2.1.8) to fill, in the<br/>            EMF+ Object Table. The value MUST be zero to 63, inclusive.|
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). <br/>            If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field.|
