---
title: "الفئة EmfPlusSetPageTransform"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetPageTransform class. سجل EmfPlusSetPageTransform يحدد عوامل القياس والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز."
type: docs
weight: 6470
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
## EmfPlusSetPageTransform class

سجل EmfPlusSetPageTransform يحدد عوامل التحجيم والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز.

```csharp
public sealed class EmfPlusSetPageTransform : EmfPlusTerminalServerRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetPageTransform](emfplussetpagetransform/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetPageTransform`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [PageScale](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pagescale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pageunit/) { get; } | يحصل على وحدة القياس لإحداثيات مساحة الصفحة، من تعداد UnitType (القسم 2.1.1.33). لا يجب أن تكون هذه القيمة UnitTypeDisplay أو UnitTypeWorld. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


