---
title: EmfPlusColorBalanceEffect Class
type: docs
weight: 170
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---

**Summary:** The ColorBalanceEffect object specifies adjustments to the relative amounts of red, green, and blue in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorBalanceEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect__1) | Initializes a new instance of the EmfPlusColorBalanceEffect class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cyan_red | int | r/w | Gets or sets a 32-bit signed integer that specifies a change in the amount of red in the<br/>            image. This value MUST be in the range -100 through 100, with effects as follows:<br/>            -100 ≤ value &lt; 0<br/>            As the value decreases, the amount of red in the image SHOULD decrease and the<br/>            amount of cyan SHOULD increase.<br/>            0 A value of 0 specifies that the amounts of red and cyan MUST NOT change.<br/>            0 &lt; value ≤ 100<br/>            As the value increases, the amount of red in the image SHOULD increase and the<br/>            amount of cyan SHOULD decrease. |
| magenta_green | int | r/w | Gets or sets a 32-bit signed integer that specifies a change in the amount of<br/>            green in the image. This value MUST be in the range -100 through 100, with effects as<br/>            follows:<br/>            -100 ≤ value &lt; 0<br/>            As the value decreases, the amount of green in the image SHOULD decrease and<br/>            the amount of magenta SHOULD increase.<br/>            0 A value of 0 specifies that the amounts of green and magenta MUST NOT change.<br/>            0 &lt; value ≤ 100<br/>            As the value increases, the amount of green in the image SHOULD increase and<br/>            the amount of magenta SHOULD decrease. |
| yellow_blue | int | r/w | Gets or sets a 32-bit signed integer that specifies a change in the amount of blue in<br/>            the image. This value MUST be in the range -100 through 100, with effects as follows:<br/>            -100 ≤ value &lt; 0<br/>            As the value decreases, the amount of blue in the image SHOULD decrease and<br/>            the amount of yellow SHOULD increase.<br/>            0 A value of 0 specifies that the amounts of blue and yellow MUST NOT change.<br/>            0 &lt; value ≤ 100<br/>            As the value increases, the amount of blue in the image SHOULD increase and the<br/>            amount of yellow SHOULD decrease. |


### Constructor: EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect__1}


```
 EmfPlusColorBalanceEffect() 
```

Initializes a new instance of the EmfPlusColorBalanceEffect class

