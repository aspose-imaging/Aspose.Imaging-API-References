---
title: EmfPlusDrawImage Class
type: docs
weight: 130
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

The EmfPlusDrawImage record specifies drawing a scaled image.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusDrawImage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawImage(source)|Initializes a new instance of the EmfPlusDrawImage class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|compressed|Gets or sets a value indicating whether the PointData is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38).<br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).|
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusImage object (section 2.2.1.4) in the EMF+<br/>            Object Table, which specifies the image to render. The value MUST be zero to 63, inclusive.|
|image_attributes_id|Gets or sets the image attributes identifier<br/>            A 32-bit unsigned integer that specifies the index of an optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table.|
|rect_data|Gets or sets the rect data<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the image.<br/>            The portion of the image specified by the SrcRect field is scaled to fit this rectangle.|
|src_rect|Gets or sets the source rect<br/>            An EmfPlusRectF object that specifies a portion of the image to be rendered.<br/>            The portion of the image specified by this rectangle is scaled to fit the destination<br/>            rectangle specified by the RectData field.|
|src_unit|Gets or sets the source unit<br/>            32-bit signed integer that specifies the units of the SrcRect field.<br/>            It MUST be the UnitTypePixel member of the UnitType enumeration (section 2.1.1.33).|
