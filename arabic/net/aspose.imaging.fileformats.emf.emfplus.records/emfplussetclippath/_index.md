---
title: "الفئة EmfPlusSetClipPath"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetClipPath class. سجل EmfPlusSetClipPath يجمع منطقة القطع الحالية مع مسار رسومي. يتم تعيين منطقة القطع الحالية الجديدة إلى نتيجة عملية CombineMode."
type: docs
weight: 6410
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
## EmfPlusSetClipPath class

السجل EmfPlusSetClipPath يجمع منطقة القص الحالية مع مسار رسومي. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة عملية CombineMode.

```csharp
public sealed class EmfPlusSetClipPath : EmfPlusClippingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetClipPath](emfplussetclippath/)(EmfPlusRecord) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusSetClipPath`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/cm/) { get; set; } | يحصل أو يعيّن CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/objectid/) { get; set; } | يحصل أو يضبط فهرس كائن EmfPlusPath (القسم 2.2.1.6) في جدول كائنات EMF+. يجب أن تكون القيمة من صفر إلى 63، شاملة. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


