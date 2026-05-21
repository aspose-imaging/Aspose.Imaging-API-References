---
title: "الفئة EmfPlusSetTextContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTextContrast. سجل EmfPlusSetTextContrast يحدد تباين النص وفقًا لقيمة تصحيح غاما."
type: docs
weight: 6500
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
## EmfPlusSetTextContrast class

سجل EmfPlusSetTextContrast يحدد تباين النص وفقًا لقيمة تصحيح غاما.

```csharp
public sealed class EmfPlusSetTextContrast : EmfPlusPropertyRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetTextContrast](emfplussettextcontrast/)(EmfPlusRecord) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusSetTextContrast`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/textcontrast/) { get; set; } | يحصل أو يضبط قيمة تصحيح غاما × 1000، التي سيتم تطبيقها على عمليات رسم النص اللاحقة. النطاق المسموح هو من 1000 إلى 2200، ممثلًا قيم غاما النص من 1.0 إلى 2.2. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


