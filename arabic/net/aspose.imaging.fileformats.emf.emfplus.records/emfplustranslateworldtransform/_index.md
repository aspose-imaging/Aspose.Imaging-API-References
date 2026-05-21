---
title: "الفئة EmfPlusTranslateWorldTransform"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusTranslateWorldTransform الفئة. سجل EmfPlusTranslateWorldTransform ينفّذ ترجمة على التحويل الحالي لفضاء العالم."
type: docs
weight: 6580
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
## EmfPlusTranslateWorldTransform class

سجل EmfPlusTranslateWorldTransform ينفذ ترجمة على تحويل مساحة العالم الحالية.

```csharp
public sealed class EmfPlusTranslateWorldTransform : EmfPlusTerminalServerRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusTranslateWorldTransform](emfplustranslateworldtransform/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusTranslateWorldTransform`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| [Dx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/dx/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32-بت تحدد المسافة الأفقية. يتم تنفيذ الترجمة بإنشاء مصفوفة تحويل عالمية جديدة من حقلي dx و dy. |
| [Dy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/dy/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32-بت تحدد قيمة المسافة العمودية. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/postmultipliedmatrix/) { get; } | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. إذا تم تعيينها، يجب أن تُضرب مصفوفة التحويل بعديًا. إذا لم تُحدد، يجب أن تُضرب مسبقًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


