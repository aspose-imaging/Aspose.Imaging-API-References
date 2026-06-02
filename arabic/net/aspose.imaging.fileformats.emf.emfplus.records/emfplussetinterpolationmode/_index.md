---
title: "الفئة EmfPlusSetInterpolationMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetInterpolationMode. سجل EmfPlusSetInterpolationMode يحدد كيفية تنفيذ مقياس الصورة بما في ذلك التمدد والتقليص"
type: docs
weight: 6460
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---
## EmfPlusSetInterpolationMode class

السجل EmfPlusSetInterpolationMode يحدد كيفية تنفيذ تحجيم الصورة، بما في ذلك التمدد والتقليص.

```csharp
public sealed class EmfPlusSetInterpolationMode : EmfPlusPropertyRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetInterpolationMode](emfplussetinterpolationmode/)(EmfPlusRecord) | يُهيئ مثيلًا جديدًا من الفئة `EmfPlusSetInterpolationMode`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [InterpolationMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/interpolationmode/) { get; set; } | يحصل أو يعيّن قيمة وضع الاستيفاء، من تعداد InterpolationMode (القسم 2.1.1.16). |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


