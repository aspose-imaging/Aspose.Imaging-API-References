---
title: "الفئة EmfPlusRotateWorldTransform"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusRotateWorldTransform. سجل EmfPlusRotateWorldTransform يقوم بإجراء دوران على تحويل الفضاء العالمي الحالي."
type: docs
weight: 6360
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
## EmfPlusRotateWorldTransform class

السجل EmfPlusRotateWorldTransform يُجري دورانًا على التحويل الحالي للفضاء العالمي.

```csharp
public sealed class EmfPlusRotateWorldTransform : EmfPlusTerminalServerRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusRotateWorldTransform](emfplusrotateworldtransform/)(EmfPlusRecord) | يهيئ مثيلاً جديداً من الفئة `EmfPlusRotateWorldTransform`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Angle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/angle/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد زاوية الدوران بالدرجات. يتم تنفيذ العملية بإنشاء مصفوفة تحويل جديدة من المخطط التالي: --------------------------------- &#x7C; sin(Angle) &#x7C; cos(Angle) &#x7C; 0 &#x7C; &#x7C; cos(Angle) &#x7C; sin(Angle) &#x7C; 0 &#x7C; --------------------------------- الشكل 2: مصفوفة تحويل الدوران يتم ضرب تحويل الفضاء العالمي الحالي بهذه المصفوفة، وتصبح النتيجة التحويل الحالي للفضاء العالمي الجديد. يحدد حقل Flags ترتيب الضرب. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/postmultipliedmatrix/) { get; } | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. إذا تم تعيينها، يجب أن تُضرب مصفوفة التحويل بعديًا. إذا لم تُحدد، يجب أن تُضرب مسبقًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


