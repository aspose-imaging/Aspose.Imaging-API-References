---
title: "الفئة EmfPlusBeginContainerNoParams"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusBeginContainerNoParams. سجل EmfPlusBeginContainerNoParams يفتح حاوية حالة رسومية جديدة."
type: docs
weight: 5970
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
## EmfPlusBeginContainerNoParams class

سجل EmfPlusBeginContainerNoParams يفتح حاوية حالة رسومية جديدة.

```csharp
public sealed class EmfPlusBeginContainerNoParams : EmfPlusStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusBeginContainerNoParams](emfplusbegincontainernoparams/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusBeginContainerNoParams`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/stackindex/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرسًا لربطه بحاوية حالة الرسومات. يجب الإشارة إلى الفهرس بواسطة سجل EmfPlusEndContainer لاحق (القسم 2.3.7.3) لإغلاق حاوية حالة الرسومات. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


