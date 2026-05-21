---
title: "الفئة EmfPlusDrawLines"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawLines. سجل EmfPlusDrawlLines يحدد رسم سلسلة من الخطوط المتصلة."
type: docs
weight: 6100
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
## EmfPlusDrawLines class

سجل EmfPlusDrawlLines يحدد رسم سلسلة من الخطوط المتصلة.

```csharp
public sealed class EmfPlusDrawLines : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawLines](emfplusdrawlines/)(EmfPlusRecord) | يهيئ مثيلاً جديداً من الفئة `EmfPlusDrawLines`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ClosedShape](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/closedshape/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [closed shape]. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) مضغوطًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم التعيين، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا تم الإلغاء، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الخطوط. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/pointdata/) { get; set; } | يحصل أو يعيّن بيانات النقاط مصفوفة من Count نقطة تحدد نقاط البداية والنهاية للخطوط التي سيتم رسمها. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/relative/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) نسبيًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم التعيين، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم الإلغاء، يحدد PointData المواقع المطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


