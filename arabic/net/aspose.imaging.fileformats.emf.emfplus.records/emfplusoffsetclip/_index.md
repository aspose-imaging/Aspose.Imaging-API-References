---
title: "الفئة EmfPlusOffsetClip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusOffsetClip. سجل EmfPlusOffsetClip يطبق تحويل إزاحة على منطقة القص الحالية للفضاء العالمي. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة تحويل الإزاحة."
type: docs
weight: 6300
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---
## EmfPlusOffsetClip class

السجل EmfPlusOffsetClip يطبق تحويل إزاحة على منطقة القص الحالية للفضاء العالمي. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة تحويل الإزاحة.

```csharp
public sealed class EmfPlusOffsetClip : EmfPlusClippingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusOffsetClip](emfplusoffsetclip/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusOffsetClip`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| [Dx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dx/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد الإزاحة الأفقية للتحويل. |
| [Dy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dy/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد الإزاحة العمودية للتحويل. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


