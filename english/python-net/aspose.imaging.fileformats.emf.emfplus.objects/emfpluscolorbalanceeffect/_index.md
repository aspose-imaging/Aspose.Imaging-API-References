---
title: EmfPlusColorBalanceEffect Class
type: docs
weight: 170
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---

The ColorBalanceEffect object specifies adjustments to the relative amounts of red, green, and blue in an image.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorBalanceEffect

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusColorBalanceEffect type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusColorBalanceEffect()|Initializes a new instance of the EmfPlusColorBalanceEffect class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|cyan_red|Gets or sets a 32-bit signed integer that specifies a change in the amount of red in the<br/>            image. This value MUST be in the range -100 through 100, with effects as follows:<br/>            -100 ≤ value < 0<br/>            As the value decreases, the amount of red in the image SHOULD decrease and the<br/>            amount of cyan SHOULD increase.<br/>            0 A value of 0 specifies that the amounts of red and cyan MUST NOT change.<br/>            0 < value ≤ 100<br/>            As the value increases, the amount of red in the image SHOULD increase and the<br/>            amount of cyan SHOULD decrease.|
|magenta_green|Gets or sets a 32-bit signed integer that specifies a change in the amount of<br/>            green in the image. This value MUST be in the range -100 through 100, with effects as<br/>            follows:<br/>            -100 ≤ value < 0<br/>            As the value decreases, the amount of green in the image SHOULD decrease and<br/>            the amount of magenta SHOULD increase.<br/>            0 A value of 0 specifies that the amounts of green and magenta MUST NOT change.<br/>            0 < value ≤ 100<br/>            As the value increases, the amount of green in the image SHOULD increase and<br/>            the amount of magenta SHOULD decrease.|
|yellow_blue|Gets or sets a 32-bit signed integer that specifies a change in the amount of blue in<br/>            the image. This value MUST be in the range -100 through 100, with effects as follows:<br/>            -100 ≤ value < 0<br/>            As the value decreases, the amount of blue in the image SHOULD decrease and<br/>            the amount of yellow SHOULD increase.<br/>            0 A value of 0 specifies that the amounts of blue and yellow MUST NOT change.<br/>            0 < value ≤ 100<br/>            As the value increases, the amount of blue in the image SHOULD increase and the<br/>            amount of yellow SHOULD decrease.|
