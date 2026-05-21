---
title: "الفئة EmfPlusGetDc"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusGetDc. سجل EmfPlusGetDC يحدد أن سجلات EMF اللاحقة التي تُعثر عليها في ملف التعريف يجب أن تُعالج."
type: docs
weight: 6250
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
## EmfPlusGetDc class

السجل EmfPlusGetDC يحدد أنه يجب معالجة سجلات EMF اللاحقة التي تُعثر عليها في ملف التعريف.

```csharp
public sealed class EmfPlusGetDc : EmfPlusControlRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusGetDc](emfplusgetdc/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusGetDc`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت غير مستخدم. يجب ضبط هذا الحقل إلى الصفر ويجب تجاهله عند الاستلام. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


