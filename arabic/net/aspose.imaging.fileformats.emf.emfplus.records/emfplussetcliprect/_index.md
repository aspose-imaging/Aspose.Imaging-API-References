---
title: "الفئة EmfPlusSetClipRect"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetClipRect. سجل EmfPlusSetClipRect يجمع منطقة القص الحالية مع مستطيل."
type: docs
weight: 6420
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
## EmfPlusSetClipRect class

السجل EmfPlusSetClipRect يجمع منطقة القص الحالية مع مستطيل.

```csharp
public sealed class EmfPlusSetClipRect : EmfPlusClippingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetClipRect](emfplussetcliprect/)(EmfPlusRecord) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusSetClipRect`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ClipRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/cliprect/) { get; set; } | يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المستطيل لاستخدامه في عملية CombineMode. |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/cm/) { get; set; } | يحصل أو يعيّن CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


