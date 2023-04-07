---
title: EmfColorAdjustment Class
type: docs
weight: 30
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfColorAdjustment type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfColorAdjustment()|Initializes a new instance of the EmfColorAdjustment class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|size|Gets or sets a 16-bit unsigned integer that specifies the size in bytes of this object. This MUST be 0x0018.|
|values|Gets or sets a 16-bit unsigned integer that specifies how to prepare the output image. This field can be <br/>            set to NULL or to any combination of values in the ColorAdjustment enumeration (section 2.1.5).|
|illuminant_index|Gets or sets a 16-bit unsigned integer that specifies the type of standard light source under which the <br/>            image is viewed, from the Illuminant enumeration (section 2.1.19).|
|red_gamma|Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the red <br/>            primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000.<br/>            A value of 10,000 means gamma correction MUST NOT be performed.|
|green_gamma|Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the green <br/>            primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. <br/>            A value of 10,000 means gamma correction MUST NOT be performed.|
|blue_gamma|Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the <br/>            blue primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. <br/>            A value of 10,000 means gamma correction MUST NOT be performed.|
|reference_black|Gets or sets a 16-bit unsigned integer that specifies the black reference for the source colors. <br/>            Any colors that are darker than this are treated as black. <br/>            This value SHOULD be in the range from zero to 4,000|
|reference_white|Gets or sets a 16-bit unsigned integer that specifies the white reference for the source colors. <br/>            Any colors that are lighter than this are treated as white. <br/>            This value SHOULD be in the range from 6,000 to 10,000.|
|contrast|Gets or sets a 16-bit signed integer that specifies the amount of contrast to be applied to the source object. <br/>            This value SHOULD be in the range from –100 to 100. A value of zero means contrast adjustment MUST NOT be performed.|
|brightness|Gets or sets a 16-bit signed integer that specifies the amount of brightness to be applied to the source object. <br/>            This value SHOULD be in the range from –100 to 100.<br/>            A value of zero means brightness adjustment MUST NOT be performed.|
|colorfullness|Gets or sets a 16-bit signed integer that specifies the amount of colorfulness to be applied to the source object. <br/>            This value SHOULD be in the range from –100 to 100. <br/>            A value of zero means colorfulness adjustment MUST NOT be performed|
|red_green_tint|Gets or sets 16-bit signed integer that specifies the amount of red or green tint adjustment to be applied <br/>            to the source object. This value SHOULD be in the range from –100 to 100. <br/>            Positive numbers adjust towards red and negative numbers adjust towards green. <br/>            A value of zero means tint adjustment MUST NOT be performed|
