---
title: "الفئة EmfPlusFillClosedCurve"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillClosedCurve. سجل EmfPlusFillClosedCurve يحدد تعبئة داخل منحنى كاردينال مغلق."
type: docs
weight: 6180
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

سجل EmfPlusFillClosedCurve يحدد تعبئة داخل منحنى كاردينال مغلق.

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusFillClosedCurve`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد EmfPlusBrush، محتواه يُحدّد بواسطة بتة S في حقل Flags. تُستخدم هذه الفرشاة لتعبئة داخل المنحنى الكاردينال المغلق. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطاً. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم التعيين، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا لم يتم التعيين، يحدد PointData المواقع المطلقة باستخدام إحداثيات عائمة 32‑بت. ---------------------- عملية تعبئة "winding" تملأ المناطق وفقاً لقاعدة "even-odd parity". وفقاً لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطاً من نقطة الاختبار إلى نقطة تقع بعيداً عن المنحنى. إذا قطع ذلك الخط المنحنى عددًا فرديًا من المرات، تكون نقطة الاختبار داخل المنحنى؛ وإلا تكون خارج المنحنى. --------------------- عملية تعبئة "alternate" تملأ المناطق وفقاً لقاعدة "non-zero". وفقاً لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطاً من نقطة الاختبار إلى نقطة تقع بعيداً عن المنحنى. عدّ عدد المرات التي يقطع فيها المنحنى الخط من اليسار إلى اليمين، وعدّ عدد المرات التي يقطع فيها المنحنى الخط من اليمين إلى اليسار. إذا كان العددان متساويين، تكون نقطة الاختبار خارج المنحنى؛ وإلا تكون داخل المنحنى. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة لونًا. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُحدد، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata/) { get; set; } | يحصل أو يعيّن بيانات النقاط مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينال مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبياً. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم التعيين، كل عنصر في PointData يحدد موقعاً في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم التعيين، يحدد PointData مواقع مطلقة وفقاً لعلامة C. ملاحظة: إذا تم تعيين هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension/) { get; set; } | يحصل أو يعيّن التوتر قيمة عائمة 32‑بت تحدد مدى انحناء المنحنى عند مروره عبر النقاط. القيمة 0.0 تشير إلى أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر انحناءً. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` من نوع "winding". تشير هذه البتة إلى طريقة تنفيذ عملية التعبئة. إذا تم التعيين، تكون التعبئة من نوع "winding". إذا لم يتم التعيين، تكون التعبئة من نوع "alternate". |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


