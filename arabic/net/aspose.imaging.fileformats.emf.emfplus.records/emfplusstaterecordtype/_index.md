---
title: "الفئة EmfPlusStateRecordType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusStateRecordType. أنواع سجلات الحالة تحدد العمليات على حالة سياق جهاز التشغيل."
type: docs
weight: 6550
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype/
---
## EmfPlusStateRecordType class

أنواع سجلات الحالة تحدد العمليات على حالة سياق جهاز التشغيل.

```csharp
public abstract class EmfPlusStateRecordType : EmfPlusRecord
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

## ملاحظات

يجب إضافة كل حاوية حالة رسومية إلى مصفوفة من حاويات الرسومات المحفوظة. حاوية حالة الرسوم لا تُكتب إلى ملف EMF+ التعريفي، لذا يمكن تحديد تنسيقها بواسطة التنفيذ.

### انظر أيضًا

* class [EmfPlusRecord](../emfplusrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


