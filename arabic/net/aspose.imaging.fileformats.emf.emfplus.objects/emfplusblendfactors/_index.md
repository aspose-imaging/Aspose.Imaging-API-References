---
title: "الفئة EmfPlusBlendFactors"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlendFactors class. يحدد كائن EmfPlusBlendFactors المواقع والعوامل لنمط المزج لفرشاة التدرج."
type: docs
weight: 5330
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
## EmfPlusBlendFactors class

يحدد كائن EmfPlusBlendFactors المواضع والعوامل لنمط الدمج لفرشاة التدرج.

```csharp
public sealed class EmfPlusBlendFactors : EmfPlusBlendBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusBlendFactors](emfplusblendfactors/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlendFactors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/blendfactors/) { get; set; } | الحصول أو تعيين مصفوفة من PositionCount قيم نقطية عائمة 32‑بت تحدد نسب الألوان عند المواقع المحددة في حقل BlendPositions. يجب أن تكون كل قيمة رقمًا بين 0.0 و 1.0 شاملًا. |
| [BlendPositions](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/blendpositions/) { get; set; } | الحصول أو تعيين مواضع المزج مصفوفة من PositionCount قيم نقطية عائمة 32‑بت تحدد نسب المسافة على طول خط التدرج. يجب أن يكون كل عنصر رقمًا بين 0.0 و 1.0 شاملًا. بالنسبة لفرشاة تدرج خطية، 0.0 تمثل نقطة البداية و 1.0 تمثل نقطة النهاية. بالنسبة لفرشاة تدرج مسار، 0.0 تمثل نقطة الوسط و 1.0 تمثل نقطة النهاية. |

### انظر أيضًا

* class [EmfPlusBlendBase](../emfplusblendbase/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


