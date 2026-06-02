---
title: "الفئة EmfPlusDrawBeziers"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawBeziers. سجل EmfPlusDrawBeziers يحدد رسم تسلسل من منحنيات بيزيير المتصلة. ترتيب نقاط بيانات بيزيير هو نقطة البداية، نقطة التحكم 1، نقطة التحكم 2، ونقطة النهاية. لمزيد من المعلومات راجع MSDNDrawBeziers"
type: docs
weight: 6030
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
## EmfPlusDrawBeziers class

سجل EmfPlusDrawBeziers يحدد رسم تسلسل من المنحنيات البيزية المتصلة. ترتيب نقاط بيانات البيزية هو نقطة البداية، نقطة التحكم الأولى، نقطة التحكم الثانية ونقطة النهاية. لمزيد من المعلومات راجع [MSDN-DrawBeziers].

```csharp
public sealed class EmfPlusDrawBeziers : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawBeziers](emfplusdrawbeziers/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawBeziers`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. إذا تم التعيين، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا لم يتم التعيين، يحدد PointData المواقع المطلقة باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم تعيين علامة Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم منحنيات بيزيير. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/) { get; set; } | يحصل أو يعيّن بيانات النقاط مصفوفة من Count نقاط تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزيير. إحداثيات النهاية لمنحنى بيزيير واحد هي إحداثيات البداية للمنحنى التالي. تُستخدم نقاط التحكم لإنتاج تأثير بيزيير. نوع البيانات في هذه المصفوفة يُحدّد بواسطة حقل Flags كما يلي: نوع البيانات معنى كائن EmfPlusPointR (القسم 2.2.2.37) إذا تم تعيين علامة P في Flags، فإن النقاط تحدد مواقع نسبية. كائن EmfPlusPointF (القسم 2.2.2.36) إذا كانت بتا P و C غير مفعّلتين في حقل Flags، فإن النقاط تحدد مواقع مطلقة. كائن EmfPlusPoint (القسم 2.2.2.35) إذا كانت بتة P غير مفعّلة وتم تفعيل بتة C في حقل Flags، فإن النقاط تحدد مواقع نسبية. لا يمر منحنى بيزيير عبر نقاط التحكم الخاصة به. نقاط التحكم تعمل كـ |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/relative/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData نسبياً. إذا تم التعيين، كل عنصر في PointData يحدد موقعاً في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم التعيين، يحدد PointData مواقع مطلقة وفقاً لعلامة C. ملاحظة: إذا تم تعيين هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


