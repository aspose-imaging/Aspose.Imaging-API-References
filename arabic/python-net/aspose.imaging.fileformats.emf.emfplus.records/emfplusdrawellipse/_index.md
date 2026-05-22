---
title: "فئة EmfPlusDrawEllipse"
type: docs
weight: 120
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---

**Summary:** The EmfPlusDrawEllipse record specifies drawing an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawEllipse(source)](#EmfPlusDrawEllipse_source_1) | يُنشئ مثيلاً جديدًا للفئة [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| مضغوط | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData مضغوطة. <br/>            إذا تم الضبط، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). <br/>            إذا تم الإلغاء، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/>            فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+<br/>            لرسم القطع الناقص. يجب أن تكون القيمة بين الصفر و 63 شاملًا. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يعيّن بيانات المستطيل<br/>            إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحدود للقطع الناقص. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawEllipse(source) {#EmfPlusDrawEllipse_source_1}


```
 EmfPlusDrawEllipse(source) 
```

يُنشئ مثيلاً جديدًا للفئة [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

