---
title: EmfPlusDrawClosedCurve
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EmfPlusDrawClosedCurve رسم شريحة أساسية مغلقة
type: docs
weight: 5920
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

يحدد سجل EmfPlusDrawClosedCurve رسم شريحة أساسية مغلقة

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType - عدد صحيح 16 بت بدون إشارة يحدد نوع السجل هذا على أنه EmfPlusDrawClosedCurve من تعداد نوع السجل (القسم 2.1.1.1). يجب أن تكون القيمة 0x4017. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)مضغوط. يشير هذا البت إلى ما إذا كان حقل PointData يحدد البيانات المضغوطة. إذا كان واضحًا ، تحدد PointData المواقع المطلقة في مساحة الإحداثيات بإحداثيات نقطة عائمة 32 بت ملاحظة إذا تم تعيين العلامة النسبية (أدناه) ، فإن هذه العلامة غير محددة ويجب تجاهلها |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت والذي يجب أن يحدد عدد 32 بت المحاذي للعدد بايت من البيانات في حقل RecordData التالي. لا يتضمن هذا الرقم رأس السجل 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وبنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | الحصول على أو تحديد معرف الكائن . فهرس كائن EmfPlusPen (القسم 2.2.1.7) في EMF + Object Table لرسم المنحنى المغلق. يجب أن تكون القيمة من صفر إلى 63 ، شاملة . |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | الحصول على أو تعيين بيانات النقطة مصفوفة من نقاط العد التي تحدد نقاط نهاية الخطوط التي تحدد الشريحة. في العمود الأساسي المغلق ، يستمر المنحنى خلال النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. يتم تحديد نوع البيانات في هذه المصفوفة بواسطة حقل الإشارات ، على النحو التالي: الكائن (القسم 2.2.2.37) إذا تم تعيين علامة P في الإشارات ، فإن النقاط تحدد المواقع النسبية. المواقع المطلقة . كائن EmfPlusPoint (القسم 2.2.2.35) إذا كان بت P واضح وتم تعيين بت C في حقل الإشارات ، تحدد النقاط المواقع النسبية. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)نسبي . يشير هذا البت إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينه ، يحدد كل عنصر في PointData موقعًا في مساحة الإحداثيات يكون نسبيًا إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة أول عنصر في PointData ، يفترض وجود موقع سابق عند الإحداثيات (0،0). إذا كان واضحًا ، تحدد PointData المواقع المطلقة وفقًا للعلامة C . ملاحظة إذا تم تعيين هذه العلامة ، فإن العلامة المضغوطة (أعلاه) غير معرَّفة ويجب تجاهلها |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد محاذاة 32 بت من بايت في السجل بأكمله ، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | الحصول على أو ضبط تحدد القيمة 0 أن الشريحة عبارة عن سلسلة من الخطوط المستقيمة. مع زيادة القيمة ، يصبح المنحنى أكثر تقريبًا. لمزيد من المعلومات ، راجع [SPLINE77] و [PETZOLD] . |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | الحصول على عدد صحيح بدون إشارة 16 بت يحدد نوع السجل. |

### أنظر أيضا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->