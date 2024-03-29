---
title: EmfPlusDrawRects
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EmfPlusDrawRects رسم سلسلة من المستطيلات
type: docs
weight: 6010
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
## EmfPlusDrawRects class

يحدد سجل EmfPlusDrawRects رسم سلسلة من المستطيلات

```csharp
public sealed class EmfPlusDrawRects : EmfPlusDrawingRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusDrawRects](emfplusdrawrects)(EmfPlusRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfPlusDrawRects`](../emfplusdrawrects) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/compressed) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت PointData مضغوطة أم لا. إذا تم تعيينها ، تحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38) . إذا تم مسحها ، تحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39) . |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت والذي يجب أن يحدد عدد 32 بت المحاذي للعدد بايت من البيانات في حقل RecordData التالي. لا يتضمن هذا الرقم رأس السجل 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وبنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/objectid) { get; set; } | الحصول على أو تحديد معرف الكائن . فهرس كائن EmfPlusPen (القسم 2.2.1.7) في EMF + Object Table لرسم المستطيلات. يجب أن تكون القيمة من صفر إلى 63 ، شاملة . |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/rectdata) { get; set; } | الحصول على أو تعيين البيانات المستقيمة مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول العد الذي يحدد بيانات المستطيل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد محاذاة 32 بت من بايت في السجل بأكمله ، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | الحصول على عدد صحيح بدون إشارة 16 بت يحدد نوع السجل. |

### أنظر أيضا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
