---
title: "فئة EmfPlusDrawBeziers"
type: docs
weight: 80
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | ينشئ مثيلاً جديداً من الفئة [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| مضغوط | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان PointData مضغوطًا. <br/>            إذا تم الضبط، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت.<br/>            إذا تم إلغاء الضبط، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت.<br/>            ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | يحصل أو يضبط معرف الكائن.<br/>            فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+<br/>            لرسم منحنيات بيزير. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يضبط بيانات النقاط<br/>            مصفوفة من نقاط Count التي تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزير. إحداثية النهاية لمنحنى بيزير واحد هي إحداثية البداية للمنحنى التالي. تُستخدم نقاط التحكم لإنتاج تأثير بيزير.<br/>            نوع البيانات في هذه المصفوفة يُحدد بواسطة حقل Flags، كما يلي: معنى نوع البيانات<br/>            كائن EmfPlusPointR (القسم 2.2.2.37)<br/>            إذا تم تعيين علم P في Flags، فإن النقاط تحدد مواقع نسبية.<br/>            كائن EmfPlusPointF (القسم 2.2.2.36)<br/>            إذا كانت بتات P و C غير مفعلة في حقل Flags، فإن النقاط تحدد مواقع مطلقة.<br/>            كائن EmfPlusPoint (القسم 2.2.2.35)<br/>            إذا كان بت P غير مفعّل وبت C مفعّل في حقل Flags، فإن النقاط تحدد مواقع نسبية.<br/>            لا يمر منحنى بيزير عبر نقاط التحكم الخاصة به. نقاط التحكم تعمل كـ |
| نسبي | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData نسبيًا.<br/>            إذا تم تعيينه، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات <br/>            يكون نسبيًا للموقع المحدد بواسطة العنصر السابق في المصفوفة. <br/>            في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات <br/>            (0,0). إذا لم يتم تعيينه، يحدد PointData مواقع مطلقة وفقًا <br/>            لعلامة C.<br/>            ملاحظة: إذا تم تعيين هذه العلامة، فإن علامة C (أعلاه) غير معرفة ويجب تجاهلها. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

