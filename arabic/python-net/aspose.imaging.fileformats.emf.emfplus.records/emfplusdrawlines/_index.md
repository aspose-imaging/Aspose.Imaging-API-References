---
title: "فئة EmfPlusDrawLines"
type: docs
weight: 150
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | يُنشئ مثيلاً جديدًا من الفئة [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [closed shape]. |
| compressed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) مضغوطًا.<br/>            تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة.<br/>            إذا تم تعيينه، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت.<br/>            إذا لم يتم تعيينه، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت.<br/>            ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/>            فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+<br/>            لرسم الخطوط. يجب أن تكون القيمة بين الصفر والـ63 شاملًا. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن بيانات النقطة<br/>            مصفوفة من نقاط Count التي تحدد نقاط البداية والنهاية للخطوط التي سيتم رسمها. |
| relative | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) نسبيًا.<br/>            تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة.<br/>            إذا تم تعيينه، يحدد كل عنصر في PointData موقعًا في مساحة الإحداثيات يكون نسبياً <br/>            إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول <br/>            في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينه، <br/>            يحدد PointData مواقع مطلقة وفقًا للعلم C.<br/>            ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

