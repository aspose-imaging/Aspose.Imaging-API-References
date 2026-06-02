---
title: "الفئة EmfPlusEndOfFile"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusEndOfFile class. سجل EmfPlusEndOfFile يحدد نهاية بيانات EMF في ملف التعريف."
type: docs
weight: 6170
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---
## EmfPlusEndOfFile class

سجل EmfPlusEndOfFile يحدد نهاية بيانات EMF+ في الملف الوصفي.

```csharp
public sealed class EmfPlusEndOfFile : EmfPlusControlRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusEndOfFile](emfplusendoffile/)(EmfPlusRecord) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusEndOfFile`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت غير مستخدم. يجب ضبط هذا الحقل إلى الصفر ويجب تجاهله عند الاستلام. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


