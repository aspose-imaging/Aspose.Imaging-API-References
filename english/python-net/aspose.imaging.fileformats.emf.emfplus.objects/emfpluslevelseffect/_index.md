---
title: EmfPlusLevelsEffect Class
type: docs
weight: 420
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | Initializes a new instance of the EmfPlusLevelsEffect class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| highlight | int | r/w | Gets or sets the Specifies how much to lighten the highlights of an image. The color<br/>            channel values at the high end of the intensity range are altered more than values near the<br/>            middle or low ends, which means an image can be lightened without losing the contrast<br/>            between the darker portions of the image.<br/>            0 ≤ value &lt; Specifies that highlights with a percent of intensity above this threshold SHOULD<br/>            100 be increased.<br/>            100 Specifies that highlights MUST NOT change. |
| mid_tone | int | r/w | Gets or sets the Specifies how much to lighten or darken the midtones of an image. Color<br/>            channel values in the middle of the intensity range are altered more than values near the high<br/>            or low ends, which means an image can be lightened or darkened without losing the contrast<br/>            between the darkest and lightest portions of the image.<br/>            -100 ≤ value &lt; 0 Specifies that midtones are made darker.<br/>            0 Specifies that midtones MUST NOT change.<br/>            0 &lt; value ≤ 100 Specifies that midtones are made lighter. |
| shadow | int | r/w | Gets or sets the Specifies how much to darken the shadows of an image. Color channel<br/>            values at the low end of the intensity range are altered more than values near the middle or<br/>            high ends, which means an image can be darkened without losing the contrast between the<br/>            lighter portions of the image.<br/>            0 Specifies that shadows MUST NOT change.<br/>            0 &lt; value ≤ 100<br/>            Specifies that shadows with a percent of intensity below this threshold are made<br/>            darker. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

Initializes a new instance of the EmfPlusLevelsEffect class

