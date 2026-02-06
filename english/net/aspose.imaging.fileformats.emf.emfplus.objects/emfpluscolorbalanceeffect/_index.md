---
title: Class EmfPlusColorBalanceEffect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusColorBalanceEffect class. The ColorBalanceEffect object specifies adjustments to the relative amounts of red green and blue in an image
type: docs
weight: 5410
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
## EmfPlusColorBalanceEffect class

The ColorBalanceEffect object specifies adjustments to the relative amounts of red, green, and blue in an image.

```csharp
public sealed class EmfPlusColorBalanceEffect : EmfPlusImageEffectsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusColorBalanceEffect](emfpluscolorbalanceeffect/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CyanRed](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/cyanred/) { get; set; } | Gets or sets a 32-bit signed integer that specifies a change in the amount of red in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 ≤ value &lt; 0 As the value decreases, the amount of red in the image SHOULD decrease and the amount of cyan SHOULD increase. 0 A value of 0 specifies that the amounts of red and cyan MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the amount of red in the image SHOULD increase and the amount of cyan SHOULD decrease. |
| [MagentaGreen](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/magentagreen/) { get; set; } | Gets or sets a 32-bit signed integer that specifies a change in the amount of green in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 ≤ value &lt; 0 As the value decreases, the amount of green in the image SHOULD decrease and the amount of magenta SHOULD increase. 0 A value of 0 specifies that the amounts of green and magenta MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the amount of green in the image SHOULD increase and the amount of magenta SHOULD decrease. |
| [YellowBlue](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/yellowblue/) { get; set; } | Gets or sets a 32-bit signed integer that specifies a change in the amount of blue in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 ≤ value &lt; 0 As the value decreases, the amount of blue in the image SHOULD decrease and the amount of yellow SHOULD increase. 0 A value of 0 specifies that the amounts of blue and yellow MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the amount of blue in the image SHOULD increase and the amount of yellow SHOULD decrease. |

### See Also

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


