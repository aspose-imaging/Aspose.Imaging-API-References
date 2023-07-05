---
title: EmfPlusBlurEffect Class
type: docs
weight: 100
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusBlurEffect type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusBlurEffect()|Initializes a new instance of the EmfPlusBlurEffect class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|blur_radius|Gets or sets a 32-bit floating-point number that specifies the blur radius in pixels,<br/>            which determines the number of pixels involved in calculating the new value of a given pixel.<br/>            This value MUST be in the range 0.0 through 255.0.|
|expand_edge|Gets or sets a 32-bit Boolean value that specifies whether the bitmap expands by<br/>            an amount equal to the value of the BlurRadius to produce soft edges. This value MUST be<br/>            one of the following:<br/>            FALSE<br/>            0x00000000<br/>            The size of the bitmap MUST NOT change, and its soft edges SHOULD be clipped to<br/>            the size of the BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            The size of the bitmap SHOULD expand by an amount equal to the BlurRadius to<br/>            produce soft edges.|
