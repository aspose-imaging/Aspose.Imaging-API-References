---
title: "الفئة EmfPlusColorCurveEffect"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusColorCurveEffect. كائن ColorCurveEffect يحدد أحد ثمانية تعديلات على منحنى اللون في الصورة."
type: docs
weight: 5420
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
## EmfPlusColorCurveEffect class

يحدد كائن ColorCurveEffect أحد ثمانية تعديلات على منحنى ألوان الصورة.

```csharp
public sealed class EmfPlusColorCurveEffect : EmfPlusImageEffectsObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusColorCurveEffect](emfpluscolorcurveeffect/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AdjustmentIntensity](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/adjustmentintensity/) { get; set; } | يحصل أو يعيّن عدد صحيح موقع 32‑بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. تتفاوت نطاقات القيم ذات المعنى لهذا الحقل وفقًا لقيمة CurveAdjustment كما يلي: نطاق تعديل التعرض: -255 ≤ value < 0 كلما انخفضت القيمة، SHOULD يقل التعرض للصورة. 0 قيمة 0 تحدد أن التعرض MUST NOT يتغير. 0 < value ≤ 255 كلما ارتفعت القيمة، SHOULD يزيد التعرض للصورة. نطاق تعديل الكثافة: -255 ≤ value < 0 كلما انخفضت القيمة، SHOULD تقل كثافة الصورة، مما ينتج صورة أغمق. 0 قيمة 0 تحدد أن الكثافة MUST NOT تتغير. 0 < value ≤ 255 كلما ارتفعت القيمة، SHOULD تزيد كثافة الصورة. نطاق تعديل التباين: -100 ≤ value < 0 كلما انخفضت القيمة، SHOULD يقل التباين في الصورة. 0 قيمة 0 تحدد أن التباين MUST NOT يتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، SHOULD يزيد التباين. نطاق تعديل الإضاءات: -100 ≤ value < 0 كلما انخفضت القيمة، SHOULD تظهر المناطق الفاتحة في الصورة أغمق. 0 قيمة 0 تحدد أن الإضاءات MUST NOT تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، SHOULD تظهر المناطق الفاتحة أفتح. نطاق تعديل الظلال: -100 ≤ value < 0 كلما انخفضت القيمة، SHOULD تظهر المناطق الداكنة في الصورة أغمق. 0 قيمة 0 تحدد أن الظلال MUST NOT تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، SHOULD تظهر المناطق الداكنة أفتح. نطاق تعديل تشبع الأبيض: 0 — 255 كلما ارتفعت القيمة، يزداد الحد الأعلى لنطاق شدة قناة اللون. نطاق تعديل تشبع الأسود: 0 — 255 كلما ارتفعت القيمة، يزداد الحد الأدنى لنطاق شدة قناة اللون. |
| [CurveAdjustment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curveadjustment/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32‑بت يحدد تعديل المنحنى لتطبيقه على الألوان في الصورة النقطية. يجب أن تكون هذه القيمة معرفة في تعداد CurveAdjustments (القسم 2.1.1.7). |
| [CurveChannel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curvechannel/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32‑بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. يجب أن تكون هذه القيمة معرفة في تعداد CurveChannel (القسم 2.1.1.8). |

### انظر أيضًا

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


