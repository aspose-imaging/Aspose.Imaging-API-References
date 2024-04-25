---
title: EmfPlusFillClosedCurve
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EmfPlusFillClosedCurve ملء الجزء الداخلي من شريحة أساسية مغلقة
type: docs
weight: 6060
url: /ar/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

يحدد سجل EmfPlusFillClosedCurve ملء الجزء الداخلي من شريحة أساسية مغلقة

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | الحصول على أو تحديد معرّف الفرشاة عدد صحيح بدون إشارة 32 بت يحدد EmfPlusBrush ، محتواه محددًا بواسطة بت S في حقل الإشارات. تستخدم هذه الفرشاة لملء الداخلية من العمود الأساسي المغلق. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)مضغوط . يشير هذا البت إلى ما إذا كان حقل PointData يحدد البيانات المضغوطة. إذا تم تعيينه ، تحدد PointData المواقع المطلقة في مساحة الإحداثيات مع إحداثيات عدد صحيح 16 بت . إذا كان واضحًا ، تحدد PointData المواقع المطلقة في مساحة إحداثيات بإحداثيات فاصلة عائمة 32 بت. تملأ العملية المناطق وفقًا لقاعدة "التكافؤ الزوجي الفردي". وفقًا لهذه القاعدة ، يمكن تحديد نقطة الاختبار لتكون داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة بعيدة من المنحنى. إذا تجاوز هذا الخط المنحنى بعدد فردي من المرات ، تكون نقطة الاختبار داخل المنحنى ؛ خلاف ذلك ، تكون نقطة الاختبار خارج المنحنى. --------------------- عملية تعبئة "بديلة" تملأ المناطق وفقًا لقاعدة "غير الصفر" . وفقًا لهذه القاعدة ، يمكن تحديد نقطة الاختبار لتكون داخل أو خارج منحنى مغلق على النحو التالي: ارسم خطًا من نقطة اختبار إلى نقطة بعيدة عن المنحنى. احسب عدد المرات التي يعبر فيها المنحنى خط الاختبار من اليسار إلى اليمين ، واحسب عدد المرات التي يعبر فيها المنحنى خط الاختبار من اليمين إلى اليسار. إذا كان هذان الرقمان متماثلين ، فإن نقطة الاختبار تقع خارج المنحنى ؛ خلاف ذلك ، تكون نقطة الاختبار داخل المنحنى. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت والذي يجب أن يحدد عدد 32 بت المحاذي للعدد بايت من البيانات في حقل RecordData التالي. لا يتضمن هذا الرقم رأس السجل 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وبنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل ملونًا. إذا تم تعيينه ، تحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1) . إذا كان مسحًا ، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1 ) في EMF + Object Table . |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | الحصول على أو تعيين بيانات النقطة مصفوفة من نقاط العد التي تحدد نقاط نهاية الخطوط التي تحدد الشريحة. في سلسلة أساسية مغلقة ، يستمر المنحنى خلال النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) نسبي . يشير هذا البت إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينه ، يحدد كل عنصر في PointData موقعًا في مساحة الإحداثيات يكون بالنسبة إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة للعنصر الأول في PointData ، يفترض وجود موقع سابق عند الإحداثيات (0،0). إذا كان واضحًا ، تحدد PointData المواقع المطلقة وفقًا للعلامة C . ملاحظة إذا تم تعيين هذه العلامة ، فإن علامة C (أعلاه) غير معرَّفة ويجب تجاهلها. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد محاذاة 32 بت من بايت في السجل بأكمله ، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | الحصول على أو ضبط تحدد القيمة 0.0 أن الشريحة عبارة عن سلسلة من الخطوط المستقيمة . مع زيادة القيمة ، يصبح المنحنى أكثر تقريبًا. لمزيد من المعلومات ، راجع [SPLINE77] و [PETZOLD] . |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | الحصول على عدد صحيح بدون إشارة 16 بت يحدد نوع السجل. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)هو ملف . يشير هذا البت إلى كيفية تنفيذ عملية التعبئة. إذا تم ضبطه ، فإن التعبئة هي تعبئة "متعرجة". إذا كان واضحًا ، فإن التعبئة تكون تعبئة "بديلة". |

### أنظر أيضا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
