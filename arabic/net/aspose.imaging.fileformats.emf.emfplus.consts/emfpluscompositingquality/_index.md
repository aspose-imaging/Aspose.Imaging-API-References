---
title: "تعداد EmfPlusCompositingQuality"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCompositingQuality. يحدد تعداد CompositingQuality مستويات الجودة لإنشاء صور مركبة."
type: docs
weight: 4850
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
## EmfPlusCompositingQuality enumeration

يحدد تعداد CompositingQuality مستويات الجودة لإنشاء صور مركبة

```csharp
public enum EmfPlusCompositingQuality : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| CompositingQualityDefault | `1` | لا يتم إجراء تصحيح جاما. يتحكم تصحيح الجاما في السطوع والتباين العامين للصورة. بدون تصحيح الجاما، قد تظهر الصور المركبة فاتحة جدًا أو داكنة جدًا. |
| CompositingQualityHighSpeed | `2` | لا يتم إجراء تصحيح جاما. يتم تفضيل سرعة التركيب على حساب الجودة. من حيث النتيجة، لا يوجد فرق بين هذه القيمة وCompositingQualityDefault. |
| CompositingQualityHighQuality | `3` | يتم إجراء تصحيح جاما. يتم تفضيل جودة التركيب على حساب السرعة. |
| CompositingQualityGammaCorrected | `4` | تمكين تصحيح الجاما للحصول على تركيب عالي الجودة مع سرعة أقل. من حيث النتيجة، لا يوجد فرق بين هذه القيمة وCompositingQualityHighQuality. |
| CompositingQualityAssumeLinear | `5` | لا يتم إجراء تصحيح جاما؛ ومع ذلك، يؤدي استخدام القيم الخطية إلى جودة أفضل من الإعداد الافتراضي بسرعة أقل قليلًا. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


