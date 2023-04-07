---
title: EmfPlusLevelsEffect Class
type: docs
weight: 420
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusLevelsEffect type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusLevelsEffect()|Initializes a new instance of the EmfPlusLevelsEffect class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|highlight|Gets or sets the Specifies how much to lighten the highlights of an image. The color<br/>            channel values at the high end of the intensity range are altered more than values near the<br/>            middle or low ends, which means an image can be lightened without losing the contrast<br/>            between the darker portions of the image.<br/>            0 ≤ value < Specifies that highlights with a percent of intensity above this threshold SHOULD<br/>            100 be increased.<br/>            100 Specifies that highlights MUST NOT change.|
|mid_tone|Gets or sets the Specifies how much to lighten or darken the midtones of an image. Color<br/>            channel values in the middle of the intensity range are altered more than values near the high<br/>            or low ends, which means an image can be lightened or darkened without losing the contrast<br/>            between the darkest and lightest portions of the image.<br/>            -100 ≤ value < 0 Specifies that midtones are made darker.<br/>            0 Specifies that midtones MUST NOT change.<br/>            0 < value ≤ 100 Specifies that midtones are made lighter.|
|shadow|Gets or sets the Specifies how much to darken the shadows of an image. Color channel<br/>            values at the low end of the intensity range are altered more than values near the middle or<br/>            high ends, which means an image can be darkened without losing the contrast between the<br/>            lighter portions of the image.<br/>            0 Specifies that shadows MUST NOT change.<br/>            0 < value ≤ 100<br/>            Specifies that shadows with a percent of intensity below this threshold are made<br/>            darker.|
