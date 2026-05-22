---
title: "فئة EmfPlusDrawCurve"
type: docs
weight: 100
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | يُنشئ مثلاً جديدًا من الفئة [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| compressed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) مضغوطًا.<br/>            تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة.<br/>            إذا تم تعيينه، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت.<br/>            إذا لم يتم تعيينه، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت.<br/>            ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| num_segments | int | r/w | يحصل أو يعيّن عدد المقاطع <br/>            عدد صحيح غير موقع 32-بت يحدد عدد مقاطع الخط التي تُكوّن المنحنى. |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/>            فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين الصفر و63، شاملًا. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن مصفوفة إما من أعداد صحيحة موقعة 32-بت أو أعداد عائمة 32-بت بطول Count تُحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| التوتر | float | r/w | يحصل أو يعيّن التوتر<br/> عدد عائم 32-بت يحدد مدى انحناء المنحنى عند مروره عبر النقاط. القيمة 0 تعني أن<br/> المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة،<br/> يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

يُنشئ مثلاً جديدًا من الفئة [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

