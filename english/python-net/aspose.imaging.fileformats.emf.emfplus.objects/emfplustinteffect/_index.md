---
title: EmfPlusTintEffect Class
type: docs
weight: 700
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---

**Summary:** The TintEffect object specifies an addition of black or white to a specified hue in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTintEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect__1) | Initializes a new instance of the EmfPlusTintEffect class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| amount | int | r/w | Gets or sets A 32-bit signed integer that specifies how much the hue is strengthened or weakened.<br/>            -100 ≤ value &lt; 0<br/>            Negative values specify how much the hue is weakened, which equates to the<br/>            addition of black.<br/>            0 A value of 0 specifies that the tint MUST NOT change.<br/>            0 &lt; value ≤ 100<br/>            Positive values specify how much the hue is strengthened, which equates to the<br/>            addition of white. |
| hue | int | r/w | Gets or sets a 32-bit signed integer that specifies the hue to which the tint effect is applied.<br/>            -180 ≤ value &lt; 0 <br/>            The color at a specified counter-clockwise rotation of the color wheel, starting<br/>            from blue.<br/>            0 A value of 0 specifies the color blue on the color wheel.<br/>            0 &lt; value ≤ 180<br/>            The color at a specified clockwise rotation of the color wheel, starting from blue |


### Constructor: EmfPlusTintEffect() {#EmfPlusTintEffect__1}


```
 EmfPlusTintEffect() 
```

Initializes a new instance of the EmfPlusTintEffect class

