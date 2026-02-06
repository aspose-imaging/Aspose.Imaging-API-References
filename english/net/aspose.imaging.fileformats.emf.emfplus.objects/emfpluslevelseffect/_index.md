---
title: Class EmfPlusLevelsEffect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLevelsEffect class. The LevelsEffect object specifies adjustments to the highlights midtones and shadows of an image
type: docs
weight: 5660
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
## EmfPlusLevelsEffect class

The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

```csharp
public sealed class EmfPlusLevelsEffect : EmfPlusImageEffectsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusLevelsEffect](emfpluslevelseffect/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Highlight](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/highlight/) { get; set; } | Gets or sets the Specifies how much to lighten the highlights of an image. The color channel values at the high end of the intensity range are altered more than values near the middle or low ends, which means an image can be lightened without losing the contrast between the darker portions of the image. 0 ≤ value &lt; Specifies that highlights with a percent of intensity above this threshold SHOULD 100 be increased. 100 Specifies that highlights MUST NOT change. |
| [MidTone](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/midtone/) { get; set; } | Gets or sets the Specifies how much to lighten or darken the midtones of an image. Color channel values in the middle of the intensity range are altered more than values near the high or low ends, which means an image can be lightened or darkened without losing the contrast between the darkest and lightest portions of the image. -100 ≤ value &lt; 0 Specifies that midtones are made darker. 0 Specifies that midtones MUST NOT change. 0 &lt; value ≤ 100 Specifies that midtones are made lighter. |
| [Shadow](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/shadow/) { get; set; } | Gets or sets the Specifies how much to darken the shadows of an image. Color channel values at the low end of the intensity range are altered more than values near the middle or high ends, which means an image can be darkened without losing the contrast between the lighter portions of the image. 0 Specifies that shadows MUST NOT change. 0 &lt; value ≤ 100 Specifies that shadows with a percent of intensity below this threshold are made darker. |

### See Also

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


