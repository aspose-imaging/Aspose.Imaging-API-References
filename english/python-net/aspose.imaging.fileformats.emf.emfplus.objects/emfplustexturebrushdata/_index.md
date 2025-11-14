---
title: EmfPlusTextureBrushData Class
type: docs
weight: 680
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | Initializes a new instance of the EmfPlusTextureBrushData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the data in the OptionalData field. <br/>            This value MUST be composed of BrushData flags (section 2.1.2.1). <br/>            The following flags are relevant to a texture brush<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Gets or sets an optional EmfPlusTextureBrushOptionalData object (section 2.2.2.46) that <br/>            specifies additional data for the texture brush. The specific contents of <br/>            this field are determined by the value of the BrushDataFlags field |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Gets or sets a 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) <br/>            that specifies how to repeat the texture image across a shape, when the <br/>            image is smaller than the area being filled. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

Initializes a new instance of the EmfPlusTextureBrushData class

