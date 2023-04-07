---
title: EmfPlusImageAttributes Class
type: docs
weight: 390
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusImageAttributes type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusImageAttributes()|Initializes a new instance of the EmfPlusImageAttributes class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|version|Gets or sets the version.|
|wrap_mode|Gets or sets a 32-bit unsigned integer that specifies how to handle edge conditions with <br/>            a value from the WrapMode enumeration (section 2.1.1.34).|
|clamp_argb_32_color|Gets or sets EmfPlusARGB (section 2.2.2.1) object that specifies the edge color to use <br/>            when the WrapMode value is WrapModeClamp. This color is visible when the <br/>            source rectangle processed by an EmfPlusDrawImage (section 2.3.4.8) record<br/>            is larger than the image itself.|
|object_clamp|Gets or sets 32-bit signed integer that specifies the object clamping behavior.<br/>            It is not used until this object is applied to an image being <br/>            drawn. This value MUST be one of the values defined in the <br/>            following table.|
