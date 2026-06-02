---
title: "الفئة EmfPlusDrawEllipse"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawEllipse. سجل EmfPlusDrawEllipse يحدد رسم إهليلج"
type: docs
weight: 6070
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
## EmfPlusDrawEllipse class

سجل EmfPlusDrawEllipse يحدد رسم إهليلج.

```csharp
public sealed class EmfPlusDrawEllipse : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawEllipse](emfplusdrawellipse/)(EmfPlusRecord) | يهيئ مثيلاً جديداً من الفئة `EmfPlusDrawEllipse`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطًا. إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا تم الإلغاء، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الإهليلج. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/rectdata/) { get; set; } | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF الذي يحدد الصندوق المحيط بالإهليلج. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


