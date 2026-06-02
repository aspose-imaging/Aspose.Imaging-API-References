---
title: "الفئة EmfPlusScaleWorldTransform"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusScaleWorldTransform class. سجل EmfPlusScaleWorldTransform يقوم بتطبيق مقياس على تحويل الفضاء العالمي الحالي."
type: docs
weight: 6380
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
## EmfPlusScaleWorldTransform class

السجل EmfPlusScaleWorldTransform يُجري تحجيمًا على التحويل الحالي للفضاء العالمي.

```csharp
public sealed class EmfPlusScaleWorldTransform : EmfPlusTerminalServerRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusScaleWorldTransform](emfplusscaleworldtransform/)(EmfPlusRecord) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusScaleWorldTransform`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/postmultipliedmatrix/) { get; } | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. إذا تم الضبط، يجب أن تُضرب مصفوفة التحويل بعديًا. إذا تم الإلغاء، يجب أن تُضرب مسبقًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Sx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sx/) { get; set; } | يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد عامل المقياس الأفقي. يتم تنفيذ المقياس بإنشاء مصفوفة تحويل جديدة من قيم الحقول Sx و Sy، كما هو موضح في الجدول التالي. ----------------- &#x7C; Sx &#x7C; 0 &#x7C; 0 &#x7C; &#x7C; 0 &#x7C; Sx &#x7C; 0 &#x7C; ----------------- الشكل 3: مصفوفة تحويل المقياس |
| [Sy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sy/) { get; set; } | يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد عامل المقياس العمودي. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


