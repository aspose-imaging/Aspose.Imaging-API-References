---
title: "الفئة EmfPlusBeginContainer"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusBeginContainer class. سجل EmfPlusBeginContainer يفتح حاوية حالة رسومية جديدة ويحدد تحويلًا لها"
type: docs
weight: 5960
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
## EmfPlusBeginContainer class

سجل EmfPlusBeginContainer يفتح حاوية حالة رسومية جديدة ويحدد تحويلًا لها.

```csharp
public sealed class EmfPlusBeginContainer : EmfPlusStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusBeginContainer](emfplusbegincontainer/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusBeginContainer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| [DestRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/destrect/) { get; set; } | يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) الذي، مع SrcRect، يحدد تحويلًا للحاوية. ينتج عن هذا التحويل SrcRect عند تطبيقه على DestRect. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/pageunit/) { get; } | يحصل على وحدة الصفحة. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/srcrect/) { get; set; } | يحصل أو يعيّن مستطيل EmfPlusRectF الذي، مع DestRect، يحدد تحويلًا للحاوية. ينتج عن هذا التحويل SrcRect عند تطبيقه على DestRect. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/stackindex/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرسًا لربطه بحاوية حالة الرسومات. يجب الإشارة إلى الفهرس بواسطة سجل EmfPlusEndContainer لاحق (القسم 2.3.7.3) لإغلاق حاوية حالة الرسومات. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


