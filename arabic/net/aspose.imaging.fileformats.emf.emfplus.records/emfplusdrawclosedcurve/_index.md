---
title: "الفئة EmfPlusDrawClosedCurve"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawClosedCurve. سجل EmfPlusDrawClosedCurve يحدد رسم منحنى كاردينال مغلق"
type: docs
weight: 6040
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

سجل EmfPlusDrawClosedCurve يحدد رسم منحنى كاردينال مغلق.

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve/)(EmfPlusRecord) | يُهيئ مثيلًا جديدًا من الفئة `EmfPlusDrawClosedCurve`. RecordType - عدد صحيح غير موقع 16 بت يحدد هذا النوع من السجلات كـ EmfPlusDrawClosedCurve من تعداد RecordType (القسم 2.1.1.1). يجب أن تكون القيمة 0x4017. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. هذا البت يشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينه، يحدد PointData مواقع مطلقة في فضاء الإحداثيات باستخدام إحداثيات صحيحة 16 بت. إذا كان غير معين، يحدد PointData مواقع مطلقة في فضاء الإحداثيات باستخدام إحداثيات عائمة 32 بت. ملاحظة: إذا تم تعيين علم Relative (أدناه)، يكون هذا العلم غير معرف ويجب تجاهله. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. الفهرس لكائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى المغلق. يجب أن تكون القيمة من صفر إلى 63، شاملة. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/) { get; set; } | يحصل أو يعيّن بيانات النقاط. مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينال مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. نوع البيانات في هذه المصفوفة يُحدد بواسطة حقل Flags، كما يلي: نوع البيانات معنى EmfPlusPointR object (القسم 2.2.2.37) إذا كان علم P مُعينًا في Flags، فإن النقاط تحدد مواقع نسبية. EmfPlusPointF object (القسم 2.2.2.36) إذا كان علما P و C مُعينين في حقل Flags، فإن النقاط تحدد مواقع مطلقة. EmfPlusPoint object (القسم 2.2.2.35) إذا كان علم P غير مُعين وعلم C مُعين في حقل Flags، فإن النقاط تحدد مواقع نسبية. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبيًا. هذا البت يشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينه، كل عنصر في PointData يحدد موقعًا في فضاء الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض موقع سابق عند الإحداثيات (0,0). إذا كان غير معين، يحدد PointData مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension/) { get; set; } | يحصل أو يعيّن الشد. عدد عائم 32 بت يحدد مدى انحناء المنحنى عند مروره عبر النقاط. القيمة 0 تعني أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر انحناءً. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


