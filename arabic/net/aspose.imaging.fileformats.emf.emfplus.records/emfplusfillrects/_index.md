---
title: EmfPlusFillRects
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EmfPlusFillRects ملء الأجزاء الداخلية لسلسلة من المستطيلات
type: docs
weight: 6110
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
## EmfPlusFillRects class

يحدد سجل EmfPlusFillRects ملء الأجزاء الداخلية لسلسلة من المستطيلات

```csharp
public sealed class EmfPlusFillRects : EmfPlusDrawingRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusFillRects](emfplusfillrects)(EmfPlusRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfPlusFillRects`](../emfplusfillrects) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/brushid) { get; set; } | الحصول على أو تحديد معرّف الفرشاة عدد صحيح بدون إشارة 32 بت يحدد الفرشاة ، يتم تحديد محتواها بواسطة بت S في حقل الإشارات. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/compressed) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`EmfPlusFillRects`](../emfplusfillrects) مضغوط . إذا تم ضبطه ، فإن RectData يحتوي على كائن EmfPlusRect (القسم 2.2.2.38). إذا تم مسحه ، فإن RectData يحتوي على كائن EmfPlusRectF (القسم 2.2.2.39) |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت والذي يجب أن يحدد عدد 32 بت المحاذي للعدد بايت من البيانات في حقل RecordData التالي. لا يتضمن هذا الرقم رأس السجل 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وبنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/iscolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل ملونًا. إذا تم تعيينه ، تحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1) . إذا كان مسحًا ، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في EMF + Object Table |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/rectdata) { get; set; } | الحصول على بيانات المستطيل أو تعيينها مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول العد الذي يحدد بيانات المستطيل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد محاذاة 32 بت من بايت في السجل بأكمله ، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | الحصول على عدد صحيح بدون إشارة 16 بت يحدد نوع السجل. |

### أنظر أيضا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->