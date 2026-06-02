---
title: "الفئة EmfPlusRestore"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusRestore. سجل EmfPlusRestore يعيد حالة الرسومات المحددة بواسطة فهرس معين من مكدس حالات الرسومات المحفوظة."
type: docs
weight: 6350
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
## EmfPlusRestore class

السجل EmfPlusRestore يستعيد حالة الرسوميات، المحددة بواسطة فهرس معين، من مكدس حالات الرسوميات المحفوظة.

```csharp
public sealed class EmfPlusRestore : EmfPlusStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusRestore](emfplusrestore/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusRestore`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/stackindex/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد المستوى المرتبط بحالة الرسومات. تم تعيين قيمة المستوى إلى حالة الرسومات بواسطة سجل EmfPlusSave السابق (القسم 2.3.7.5). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


