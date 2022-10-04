---
title: EmfPlusSetPageTransform
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EmfPlusSetPageTransform عوامل القياس والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز.
type: docs
weight: 6350
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
## EmfPlusSetPageTransform class

يحدد سجل EmfPlusSetPageTransform عوامل القياس والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز.

```csharp
public sealed class EmfPlusSetPageTransform : EmfPlusTerminalServerRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusSetPageTransform](emfplussetpagetransform)(EmfPlusRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfPlusSetPageTransform`](../emfplussetpagetransform) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت والذي يجب أن يحدد عدد 32 بت المحاذي للعدد بايت من البيانات في حقل RecordData التالي. لا يتضمن هذا الرقم رأس السجل 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وبنية السجل. |
| [PageScale](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pagescale) { get; set; } | الحصول على أو تعيين قيمة النقطة العائمة 32 بت التي تحدد عامل المقياس لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pageunit) { get; } | الحصول على وحدة قياس إحداثيات مساحة الصفحة ، من تعداد UnitType (القسم 2.1.1.33). يجب ألا تكون هذه القيمة هي UnitTypeDisplay أو UnitTypeWorld. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد محاذاة 32 بت من بايت في السجل بأكمله ، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | الحصول على عدد صحيح بدون إشارة 16 بت يحدد نوع السجل. |

### أنظر أيضا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->