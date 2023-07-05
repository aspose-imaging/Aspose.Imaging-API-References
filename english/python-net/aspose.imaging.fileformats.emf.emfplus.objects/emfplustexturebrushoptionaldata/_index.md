---
title: EmfPlusTextureBrushOptionalData Class
type: docs
weight: 690
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusTextureBrushOptionalData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusTextureBrushOptionalData()|Initializes a new instance of the EmfPlusTextureBrushOptionalData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|transform_matrix|Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) <br/>            that specifies a world space to device space transform for the<br/>             texture brush. This field MUST be present if the BrushDataTransform <br/>            flag is set in the BrushDataFlags field of the EmfPlusTextureBrushData object.|
|image_object|Gets or sets an optional EmfPlusImage object (section 2.2.1.4) that specifies the<br/>            brush texture. This field MUST be present if the size of the <br/>            EmfPlusObject record (section 2.3.5.1) that defines this texture <br/>            brush is large enough to accommodate an EmfPlusImage object in <br/>            addition to the required fields of the EmfPlusTextureBrushData object <br/>            and optionally an EmfPlusTransformMatrix object.|
