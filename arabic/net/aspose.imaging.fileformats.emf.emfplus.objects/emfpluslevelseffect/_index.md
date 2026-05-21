---
title: "الفئة EmfPlusLevelsEffect"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLevelsEffect. كائن LevelsEffect يحدد تعديلات على الإضاءات والوسطيات والظلال في الصورة."
type: docs
weight: 5660
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
## EmfPlusLevelsEffect class

كائن LevelsEffect يحدد التعديلات على الإضاءات، النغمات المتوسطة، والظلال في الصورة.

```csharp
public sealed class EmfPlusLevelsEffect : EmfPlusImageEffectsObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusLevelsEffect](emfpluslevelseffect/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Highlight](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/highlight/) { get; set; } | يحصل أو يعيّن ما يحدد مقدار إضاءة الإضاءات في الصورة. قيم قناة اللون في الطرف العالي من نطاق الشدة تُعدَّل أكثر من القيم القريبة من الوسط أو الطرف المنخفض، مما يعني أنه يمكن إضاءة الصورة دون فقدان التباين بين الأجزاء الداكنة من الصورة. 0 ≤ value < يحدد أن الإضاءات التي تتجاوز نسبة الشدة هذا العتبة SHOULD أن تُزاد. 100 يحدد أن الإضاءات MUST NOT تتغير. |
| [MidTone](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/midtone/) { get; set; } | يحصل أو يعيّن ما يحدد مقدار إضاءة أو تعتيم الوسطيات في الصورة. قيم قناة اللون في وسط نطاق الشدة تُعدَّل أكثر من القيم القريبة من الطرفين العالي أو المنخفض، مما يعني أنه يمكن إضاءة أو تعتيم الصورة دون فقدان التباين بين الأجزاء الأ darkest والأكثر إضاءة. -100 ≤ value < 0 يحدد أن الوسطيات تُصبح أغمق. 0 يحدد أن الوسطيات MUST NOT تتغير. 0 < value ≤ 100 يحدد أن الوسطيات تُصبح أفتح. |
| [Shadow](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/shadow/) { get; set; } | يحصل أو يعيّن ما يحدد مقدار تعتيم الظلال في الصورة. قيم قناة اللون في الطرف المنخفض من نطاق الشدة تُعدَّل أكثر من القيم القريبة من الوسط أو الطرف العالي، مما يعني أنه يمكن تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر إضاءة. 0 يحدد أن الظلال MUST NOT تتغير. 0 < value ≤ 100 يحدد أن الظلال التي تقل نسبتها عن هذا العتبة تصبح أغمق. |

### انظر أيضًا

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


