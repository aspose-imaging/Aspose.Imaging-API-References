---
title: EmfPlusImageAttributes Class
type: docs
weight: 390
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | Initializes a new instance of the EmfPlusImageAttributes class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | Gets or sets EmfPlusARGB (section 2.2.2.1) object that specifies the edge color to use <br/>            when the WrapMode value is WrapModeClamp. This color is visible when the <br/>            source rectangle processed by an EmfPlusDrawImage (section 2.3.4.8) record<br/>            is larger than the image itself. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | Gets or sets 32-bit signed integer that specifies the object clamping behavior.<br/>            It is not used until this object is applied to an image being <br/>            drawn. This value MUST be one of the values defined in the <br/>            following table. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Gets or sets the version. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to handle edge conditions with <br/>            a value from the WrapMode enumeration (section 2.1.1.34). |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

Initializes a new instance of the EmfPlusImageAttributes class

