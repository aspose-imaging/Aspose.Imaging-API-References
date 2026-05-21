---
title: "الفئة EmfPlusFillRegion"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillRegion. يُحدِّد سجل EmfPlusFillRegion تعبئة داخل منطقة رسومية."
type: docs
weight: 6240
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
## EmfPlusFillRegion class

السجل EmfPlusFillRegion يحدد تعبئة داخل منطقة رسومية.

```csharp
public sealed class EmfPlusFillRegion : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusFillRegion](emfplusfillregion/)(EmfPlusRecord) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusFillRegion`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة: عدد صحيح غير موقع 32‑بت يحدد الفرشاة، محتواها يحدد بواسطة بت S في حقل Flags. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة لونًا. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُحدد، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusRegion (القسم 2.2.1.8) للتعبئة في جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


