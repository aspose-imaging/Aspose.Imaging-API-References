---
title: EmfPlusDrawEllipse Class
type: docs
weight: 120
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---

The EmfPlusDrawEllipse record specifies drawing an ellipse.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawEllipse

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusDrawEllipse type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawEllipse(source)|Initializes a new instance of the EmfPlusDrawEllipse class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusPen (section 2.2.1.7) object in the EMF+<br/>            Object Table to draw the ellipse. The value MUST be zero to 63, inclusive.|
|compressed|Gets or sets a value indicating whether the PointData is compressed. <br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38). <br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).|
|rect_data|Gets or sets the rectangle data<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse.|
