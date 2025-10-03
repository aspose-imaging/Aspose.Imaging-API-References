---
title: EmfPlusBlurEffect Class
type: docs
weight: 100
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | Initializes a new instance of the EmfPlusBlurEffect class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Gets or sets a 32-bit floating-point number that specifies the blur radius in pixels,<br/>            which determines the number of pixels involved in calculating the new value of a given pixel.<br/>            This value MUST be in the range 0.0 through 255.0. |
| expand_edge | bool | r/w | Gets or sets a 32-bit Boolean value that specifies whether the bitmap expands by<br/>            an amount equal to the value of the BlurRadius to produce soft edges. This value MUST be<br/>            one of the following:<br/>            FALSE<br/>            0x00000000<br/>            The size of the bitmap MUST NOT change, and its soft edges SHOULD be clipped to<br/>            the size of the BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            The size of the bitmap SHOULD expand by an amount equal to the BlurRadius to<br/>            produce soft edges. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

Initializes a new instance of the EmfPlusBlurEffect class

