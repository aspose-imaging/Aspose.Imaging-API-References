---
title: "الفئة EmfPlusSetTextRenderingHint"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTextRenderingHint. سجل EmfPlusSetTextRenderingHint يحدد جودة عرض النص بما في ذلك نوع مضاد التعرجات."
type: docs
weight: 6510
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/
---
## EmfPlusSetTextRenderingHint class

سجل EmfPlusSetTextRenderingHint يحدد جودة عرض النص، بما في ذلك نوع مضاد التعرجات.

```csharp
public sealed class EmfPlusSetTextRenderingHint : EmfPlusPropertyRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetTextRenderingHint](emfplussettextrenderinghint/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusSetTextRenderingHint`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [TextRenderingHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/textrenderinghint/) { get; set; } | يحصل أو يعيّن قيمة تلميح عرض النص، من تعداد TextRenderingHint (القسم 2.1.1.32)، الذي يحدد الجودة المستخدمة في عرض النص اللاحق. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


