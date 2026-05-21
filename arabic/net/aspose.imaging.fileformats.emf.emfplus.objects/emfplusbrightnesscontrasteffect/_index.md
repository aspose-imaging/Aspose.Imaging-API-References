---
title: "Class EmfPlusBrightnessContrastEffect"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBrightnessContrastEffect class. يحدد كائن BrightnessContrastEffect توسعًا أو انكماشًا لأفتح وأظلم مناطق الصورة."
type: docs
weight: 5380
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
## EmfPlusBrightnessContrastEffect class

يحدد كائن BrightnessContrastEffect توسعًا أو انكماشًا لأفتح وأظلم مناطق الصورة.

```csharp
public sealed class EmfPlusBrightnessContrastEffect : EmfPlusImageEffectsObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusBrightnessContrastEffect](emfplusbrightnesscontrasteffect/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrightnessLevel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/brightnesslevel/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد مستوى السطوع. This value MUST be in the range -255 through 255, with effects as follows: -255 ≤ value &lt; 0 As the value decreases, the brightness of the image SHOULD decrease. 0 A value of 0 specifies that the brightness MUST NOT change. 0 &lt; value ≤ 255 As the value increases, the brightness of the image SHOULD increase. |
| [ContrastLevel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/contrastlevel/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد مستوى التباين. This value MUST be in the range -100 through 100, with effects as follows: -100 ≤ value &lt; 0 As the value decreases, the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the contrast of the image SHOULD increase. |

### انظر أيضًا

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


