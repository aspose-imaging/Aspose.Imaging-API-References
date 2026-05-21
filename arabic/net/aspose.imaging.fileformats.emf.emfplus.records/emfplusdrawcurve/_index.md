---
title: "الفئة EmfPlusDrawCurve"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawCurve. سجل EmfPlusDrawCurve يحدد رسم منحنى كاردينال. ملاحظة: ObjectID هو بايت واحد يحدد فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF لرسم المنحنى. يجب أن تكون القيمة بين 0 و 63 شاملًا."
type: docs
weight: 6050
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
## EmfPlusDrawCurve class

سجل EmfPlusDrawCurve يحدد رسم منحنى كاردينال. ملاحظة: ObjectID (بايت واحد): فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين 0 و 63 شاملًا.

```csharp
public sealed class EmfPlusDrawCurve : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawCurve](emfplusdrawcurve/)(EmfPlusRecord) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusDrawCurve`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) مضغوطًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم التعيين، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا تم الإلغاء، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [NumSegments](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/numsegments/) { get; set; } | يحصل أو يعيّن عدد المقاطع عدد صحيح غير موقع 32‑بت يحدد عدد مقاطع الخط التي تشكّل المنحنى. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/pointdata/) { get; set; } | يحصل أو يعيّن مصفوفة إما من أعداد صحيحة موقعة 32‑بت أو أعداد عائمة 32‑بت بطول Count تُحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/tension/) { get; set; } | يحصل أو يعيّن الشد. عدد عائم 32 بت يحدد مدى انحناء المنحنى عند مروره عبر النقاط. القيمة 0 تعني أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر انحناءً. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


