---
title: "الفئة EmfPlusSetAntiAliasMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetAntiAliasMode. سجل EmfPlusSetAntiAliasMode يحدد وضع مكافحة التعرجات لإخراج النص."
type: docs
weight: 6400
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
## EmfPlusSetAntiAliasMode class

السجل EmfPlusSetAntiAliasMode يحدد وضع مكافحة التعرجات لإخراج النص.

```csharp
public sealed class EmfPlusSetAntiAliasMode : EmfPlusPropertyRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetAntiAliasMode](emfplussetantialiasmode/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetAntiAliasMode`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AntiAliasing](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/antialiasing/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [anti aliasing]. إذا تم تعيينها، يجب تنفيذ مكافحة التعرجات. إذا لم تُحدد، يجب عدم تنفيذ مكافحة التعرجات. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [SmoothingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/smoothingmode/) { get; set; } | يحصل أو يعيّن وضع التنعيم. (7 بتات): قيمة وضع التنعيم، من تعداد SmoothingMode (القسم 2.1.1.28). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


