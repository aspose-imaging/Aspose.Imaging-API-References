---
title: EmfPlusBrightnessContrastEffect Class
type: docs
weight: 140
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---

**Summary:** The BrightnessContrastEffect object specifies an expansion or contraction of the lightest and darkest areas of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBrightnessContrastEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect__1) | Initializes a new instance of the EmfPlusBrightnessContrastEffect class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brightness_level | int | r/w | Gets or sets a 32-bit signed integer that specifies the brightness level. This<br/>            value MUST be in the range -255 through 255, with effects as follows:<br/>            -255 ≤ value &lt; 0 As the value decreases, the brightness of the image SHOULD decrease.<br/>            0 A value of 0 specifies that the brightness MUST NOT change.<br/>            0 &lt; value ≤ 255 As the value increases, the brightness of the image SHOULD increase. |
| contrast_level | int | r/w | Gets or sets a 32-bit signed integer that specifies the contrast level. This value<br/>            MUST be in the range -100 through 100, with effects as follows:<br/>            -100 ≤ value &lt; 0 As the value decreases, the contrast of the image SHOULD decrease.<br/>            0 A value of 0 specifies that the contrast MUST NOT change.<br/>            0 &lt; value ≤ 100 As the value increases, the contrast of the image SHOULD increase. |


### Constructor: EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect__1}


```
 EmfPlusBrightnessContrastEffect() 
```

Initializes a new instance of the EmfPlusBrightnessContrastEffect class

