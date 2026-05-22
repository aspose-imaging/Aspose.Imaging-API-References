---
title: "EmfPlusFillClosedCurve فئة"
type: docs
weight: 230
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | يحصل أو يعيّن معرف الفرشاة<br/>            عدد صحيح غير موقع 32 بت يحدد EmfPlusBrush، محتواه يتم تحديده بواسطة البت S في حقل Flags. تُستخدم هذه الفرشاة لملء داخل المنحنى القاردي المغلق. |
| compressed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) مضغوطًا.<br/>            هذه البتة تشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة.<br/>            إذا تم تعيينها، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16 بت.<br/>            إذا لم يتم تعيينها، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32 بت.<br/>            ----------------------<br/>            عملية تعبئة \"winding\" تملأ المناطق وفقًا لقاعدة \"التساوي الزوجي-الفردي\".<br/>            وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. إذا قطع الخط المنحنى عددًا فرديًا من المرات، تكون نقطة الاختبار داخل المنحنى؛ وإلا تكون خارج المنحنى.<br/>            ---------------------<br/>            عملية تعبئة \"alternate\" تملأ المناطق وفقًا لقاعدة \"غير الصفر\".<br/>            وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. عد عدد المرات التي يقطع فيها المنحنى خط الاختبار من اليسار إلى اليمين، وعد عدد المرات التي يقطع فيها المنحنى خط الاختبار من اليمين إلى اليسار. إذا كان الرقمان متساويين، تكون نقطة الاختبار خارج المنحنى؛ وإلا تكون داخل المنحنى. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة.<br/>            إذا تم التعيين، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1).<br/>            إذا لم يتم التعيين، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن بيانات النقاط<br/>            مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى.<br/>            في منحنى كارديال مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. |
| relative | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) نسبيًا.<br/>            هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة.<br/>            إذا تم تعيينها، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون<br/>            نسبيًا للموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة<br/>            العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0).<br/>            إذا لم يتم تعيينها، يحدد PointData مواقع مطلقة وفقًا لعلامة C.<br/>            ملاحظة: إذا تم تعيين هذه العلامة، فإن علامة C (أعلاه) غير معرفة ويجب تجاهلها. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| التوتر | float | r/w | يحصل أو يعيّن التوتر<br/>            قيمة عائمة 32 بت تحدد مدى انحناء المنحنى عند مرورها عبر النقاط. القيمة 0.0 تعني أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |
| winding | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) من نوع \"winding\".<br/>            هذه البتة تشير إلى طريقة تنفيذ عملية التعبئة.<br/>            إذا تم تعيينها، تكون التعبئة من نوع \"winding\". إذا لم يتم تعيينها، تكون التعبئة من نوع \"alternate\". |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

