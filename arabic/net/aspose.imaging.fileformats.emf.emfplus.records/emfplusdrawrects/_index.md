---
title: "الفئة EmfPlusDrawRects"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawRects class. سجل EmfPlusDrawRects يحدد رسم سلسلة من المستطيلات"
type: docs
weight: 6130
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
## EmfPlusDrawRects class

سجل EmfPlusDrawRects يحدد رسم سلسلة من المستطيلات.

```csharp
public sealed class EmfPlusDrawRects : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawRects](emfplusdrawrects/)(EmfPlusRecord) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawRects`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطًا. إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا تم الإلغاء، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/objectid/) { get; set; } | يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المستطيلات. يجب أن تكون القيمة من صفر إلى 63، شاملة. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/rectdata/) { get; set; } | يحصل أو يضبط بيانات المستطيل. مصفوفة إما كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تحدد بيانات المستطيل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


