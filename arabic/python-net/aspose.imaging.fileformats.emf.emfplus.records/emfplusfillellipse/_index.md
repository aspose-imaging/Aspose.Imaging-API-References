---
title: "فئة EmfPlusFillEllipse"
type: docs
weight: 240
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---

**Summary:** The EmfPlusFillEllipse record specifies filling the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusFillEllipse(source)](#EmfPlusFillEllipse_source_1) | ينشئ مثيلاً جديداً من الفئة [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | يحصل أو يضبط معرف الفرشاة<br/>            عدد صحيح غير موقع 32‑بت يحدد الفرشاة، محتواها يتم تحديده بواسطة بت S في حقل Flags. تُستخدم هذه التعريفية <br/>            لملء داخل الإهليلج. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة.<br/>            إذا تم التعيين، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1).<br/>            إذا لم يتم التعيين، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| is_compressed | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مضغوطًا.<br/>            إذا تم الضبط، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). <br/>            إذا تم إلغاء الضبط، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يضبط بيانات المستطيل<br/>            إما كائن EmfPlusRect أو EmfPlusRectF الذي يحدد الصندوق المحيط بالإهليلج. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusFillEllipse(source) {#EmfPlusFillEllipse_source_1}


```
 EmfPlusFillEllipse(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

