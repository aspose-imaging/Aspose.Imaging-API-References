---
title: EmfPlusFillEllipse Class
type: docs
weight: 240
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---

The EmfPlusFillEllipse record specifies filling the interior of an ellipse

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillEllipse

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusFillEllipse type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusFillEllipse(source)|Initializes a new instance of the EmfPlusFillEllipse class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1).<br/>            If clear, BrushId contains the index of an EmfPlusBrush object <br/>            (section 2.2.1.1) in the EMF+ Object Table.|
|is_compressed|Gets or sets a value indicating whether this instance is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38). <br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that specifies the brush, the content of which<br/>            is determined by the S bit in the Flags field. This definition is used <br/>            to fill the interior of the ellipse|
|rect_data|Gets or sets the rect data<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse|
