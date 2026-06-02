---
title: "فئة EmfPlusSetWorldTransform"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetWorldTransform فئة. يضبط سجل EmfPlusSetWorldTransform التحويل العالمي وفقًا للقيم في مصفوفة تحويل محددة."
type: docs
weight: 6540
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
## EmfPlusSetWorldTransform class

سجل EmfPlusSetWorldTransform يضبط تحويل العالم وفقًا للقيم الموجودة في مصفوفة التحويل المحددة.

```csharp
public sealed class EmfPlusSetWorldTransform : EmfPlusTerminalServerRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetWorldTransform](emfplussetworldtransform/)(EmfPlusRecord) | يُهيئ نسخة جديدة من الفئة `EmfPlusSetWorldTransform`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/matrixdata/) { get; set; } | يحصل أو يعيّن كائن EmfPlusTransformMatrix (القسم 2.2.2.47) الذي يحدد التحويل العالمي الحالي الجديد. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


