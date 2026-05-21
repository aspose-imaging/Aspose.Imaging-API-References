---
title: "الفئة EmfPlusSetClipRegion"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetClipRegion. سجل EmfPlusSetClipRegion يجمع منطقة القص الحالية مع منطقة رسومية أخرى. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة تنفيذ عملية CombineMode على منطقة القص الحالية السابقة والكائن EmfPlusRegion المحدد."
type: docs
weight: 6430
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
## EmfPlusSetClipRegion class

السجل EmfPlusSetClipRegion يجمع منطقة القص الحالية مع منطقة رسومية أخرى. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة عملية CombineMode على منطقة القص الحالية السابقة والكائن EmfPlusRegion المحدد.

```csharp
public sealed class EmfPlusSetClipRegion : EmfPlusClippingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetClipRegion](emfplussetclipregion/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusSetClipRegion`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/cm/) { get; set; } | يحصل أو يعيّن CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/objectid/) { get; set; } | يحصل أو يعيّن فهرس كائن EmfPlusRegion (القسم 2.2.1.8) في جدول كائنات EMF+. يجب أن تكون القيمة من 0 إلى 63، شاملة. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


