---
title: EmfPlusTextureBrushData Class
type: docs
weight: 680
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusTextureBrushData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusTextureBrushData()|Initializes a new instance of the EmfPlusTextureBrushData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|brush_data_flags|Gets or sets a 32-bit unsigned integer that specifies the data in the OptionalData field. <br/>            This value MUST be composed of BrushData flags (section 2.1.2.1). <br/>            The following flags are relevant to a texture brush<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform|
|wrap_mode|Gets or sets a 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) <br/>            that specifies how to repeat the texture image across a shape, when the <br/>            image is smaller than the area being filled.|
|optional_data|Gets or sets an optional EmfPlusTextureBrushOptionalData object (section 2.2.2.46) that <br/>            specifies additional data for the texture brush. The specific contents of <br/>            this field are determined by the value of the BrushDataFlags field|
