---
title: "الفئة EmfPlusEndContainer"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusEndContainer. سجل EmfPlusEndContainer يغلق حاوية حالة الرسومات التي تم فتحها مسبقًا بواسطة عملية بدء الحاوية."
type: docs
weight: 6160
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
## EmfPlusEndContainer class

سجل EmfPlusEndContainer يغلق حاوية حالة رسومية تم فتحها مسبقًا بواسطة عملية بدء الحاوية.

```csharp
public sealed class EmfPlusEndContainer : EmfPlusStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusEndContainer](emfplusendcontainer/)(EmfPlusRecord) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusEndContainer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/stackindex/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد فهرس حاوية حالة الرسومات. يجب أن يتطابق الفهرس مع القيمة المرتبطة بحاوية حالة الرسومات التي تم فتحها بواسطة سجل EmfPlusBeginContainer السابق (القسم 2.3.7.1) أو سجل EmfPlusBeginContainerNoParams (القسم 2.3.7.2). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


