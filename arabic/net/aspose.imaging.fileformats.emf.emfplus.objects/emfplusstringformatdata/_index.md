---
title: "الفئة EmfPlusStringFormatData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusStringFormatData. يحدد كائن EmfPlusStringFormatData مواضع الفواصل (tab stops) ومواقع الأحرف لسلسلة رسومية."
type: docs
weight: 5910
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
## EmfPlusStringFormatData class

كائن EmfPlusStringFormatData يحدد مواضع التبويب ومواقع الأحرف لسلسلة رسومية.

```csharp
public sealed class EmfPlusStringFormatData : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusStringFormatData](emfplusstringformatdata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CharRange](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/charrange/) { get; set; } | الحصول أو تعيين مصفوفة اختيارية من كائنات RangeCount EmfPlusCharacterRange التي تحدد نطاق مواضع الأحرف داخل سلسلة نصية. يتم تعريف المنطقة المحيطة بواسطة مساحة العرض التي يشغلها مجموعة الأحرف المحددة بنطاق الأحرف. يجب أن يكون هذا الحقل موجودًا إذا كانت قيمة الحقل RangeCount في كائن EmfPlusStringFormat أكبر من 0. |
| [TabStops](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/tabstops/) { get; set; } | الحصول أو تعيين مصفوفة اختيارية من القيم العشرية التي تحدد مواقع الفواصل (tab stops) الاختيارية لهذا الكائن. كل قيمة فاصل تمثل عدد المسافات بين الفواصل أو، بالنسبة لأول فاصل، عدد المسافات بين بداية سطر النص وأول فاصل. يجب أن يكون هذا الحقل موجودًا إذا كانت قيمة الحقل TabStopCount في كائن EmfPlusStringFormat أكبر من 0. |

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


