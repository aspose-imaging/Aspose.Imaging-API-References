---
title: "الفئة EmfPlusSave"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSave فئة. يسجل EmfPlusSave حالة الرسومات المحددة بواسطة فهرس محدد على مكدس حالات الرسومات المحفوظة"
type: docs
weight: 6370
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
## EmfPlusSave class

السجل EmfPlusSave يحفظ حالة الرسوميات، المحددة بواسطة فهرس معين، على مكدس حالات الرسوميات المحفوظة.

```csharp
public sealed class EmfPlusSave : EmfPlusStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSave](emfplussave/)(EmfPlusRecord) | يُهيئ نسخة جديدة من الفئة `EmfPlusSave`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave/stackindex/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد مستوىً يرتبط بحالة الرسومات. يمكن استخدام قيمة المستوى بواسطة سجل EmfPlusRestore اللاحق (القسم 2.3.7.4) لاسترجاع حالة الرسومات. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


