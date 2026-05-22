---
title: "الفئة EmfPlusFillPolygon"
type: docs
weight: 270
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | ينشئ مثيلًا جديدًا للفئة [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | الحصول أو تعيين معرف الفرشاة<br/>            عدد صحيح غير موقع 32 بت يحدد الفرشاة، المحتوى <br/>            الذي يتم تحديده بواسطة البت S في حقل Flags. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_color | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل لونيًا.<br/>            إذا تم تعيينه، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). <br/>            إذا لم يتم تعيينه، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| is_compressed | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل مضغوطًا.<br/>            إذا تم تعيينه، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16 بت. إذا لم يتم تعيينه، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32 بت. |
| is_relative | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل نسبيًا.<br/>            إذا تم تعيينه، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبيًا للموقع المحدد بواسطة العنصر السابق <br/>            في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينه، يحدد PointData مواقع مطلقة وفقًا للعلامة C. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | الحصول أو تعيين بيانات النقطة<br/>            مصفوفة من Count نقطة تحدد رؤوس المضلع. <br/>            أول نقطتين في المصفوفة تحددان الجانب الأول من المضلع. <br/>            كل نقطة إضافية تحدد جانبًا جديدًا، رؤوسه <br/>            تشمل النقطة والنقطة السابقة. إذا لم تتطابق النقطة الأخيرة و <br/>            النقطة الأولى، فإنهما تحددان الجانب الأخير من المضلع. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

ينشئ مثيلًا جديدًا للفئة [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

