---
title: "فئة EmfPlusDrawClosedCurve"
type: docs
weight: 90
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) .<br/> RecordType - عدد صحيح غير موقع 16-بت يحدد نوع هذا السجل كـ EmfPlusDrawClosedCurve<br/> من تعداد RecordType (القسم 2.1.1.1). يجب أن تكون القيمة 0x4017. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| compressed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) مضغوطًا.<br/>            تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة.<br/>            إذا تم تعيينه، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت.<br/>            إذا لم يتم تعيينه، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت.<br/>            ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/> فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+<br/> لرسم المنحنى المغلق. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن بيانات النقاط<br/> مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينال مغلق،<br/> يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة.<br/> نوع البيانات في هذه المصفوفة يُحدّد بحقل Flags، كما يلي: معنى نوع البيانات<br/> كائن EmfPlusPointR (القسم 2.2.2.37)<br/> إذا تم ضبط علامة P في Flags، فإن النقاط تحدد مواقع نسبية.<br/> كائن EmfPlusPointF (القسم 2.2.2.36)<br/> إذا تم ضبط بتتي P و C في حقل Flags، فإن النقاط تحدد مواقع مطلقة.<br/> كائن EmfPlusPoint (القسم 2.2.2.35)<br/> إذا كانت علامة P غير مضبوطة وعلامة C مضبوطة في حقل Flags، فإن النقاط تحدد مواقع نسبية. |
| relative | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) نسبيًا.<br/>            تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة.<br/>            إذا تم تعيينه، يحدد كل عنصر في PointData موقعًا في مساحة الإحداثيات يكون نسبياً <br/>            إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول <br/>            في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينه، <br/>            يحدد PointData مواقع مطلقة وفقًا للعلم C.<br/>            ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| التوتر | float | r/w | يحصل أو يعيّن التوتر<br/> عدد عائم 32-بت يحدد مدى انحناء المنحنى عند مروره عبر النقاط. القيمة 0 تعني أن<br/> المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة،<br/> يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) .<br/> RecordType - عدد صحيح غير موقع 16-بت يحدد نوع هذا السجل كـ EmfPlusDrawClosedCurve<br/> من تعداد RecordType (القسم 2.1.1.1). يجب أن تكون القيمة 0x4017.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

