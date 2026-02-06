---
title: Class EmfPlusTintEffect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTintEffect class. The TintEffect object specifies an addition of black or white to a specified hue in an image
type: docs
weight: 5950
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
## EmfPlusTintEffect class

The TintEffect object specifies an addition of black or white to a specified hue in an image.

```csharp
public sealed class EmfPlusTintEffect : EmfPlusImageEffectsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusTintEffect](emfplustinteffect/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Amount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/amount/) { get; set; } | Gets or sets A 32-bit signed integer that specifies how much the hue is strengthened or weakened. -100 ≤ value &lt; 0 Negative values specify how much the hue is weakened, which equates to the addition of black. 0 A value of 0 specifies that the tint MUST NOT change. 0 &lt; value ≤ 100 Positive values specify how much the hue is strengthened, which equates to the addition of white. |
| [Hue](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/hue/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the hue to which the tint effect is applied. -180 ≤ value &lt; 0 The color at a specified counter-clockwise rotation of the color wheel, starting from blue. 0 A value of 0 specifies the color blue on the color wheel. 0 &lt; value ≤ 180 The color at a specified clockwise rotation of the color wheel, starting from blue |

### See Also

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


