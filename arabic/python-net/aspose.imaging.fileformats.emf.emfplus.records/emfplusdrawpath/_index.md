---
title: "فئة EmfPlusDrawPath"
type: docs
weight: 160
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---

**Summary:** The EmfPlusDrawPath record specifies drawing a graphics path.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawPath(source)](#EmfPlusDrawPath_source_1) | يُنشئ مثلاً جديدًا من الفئة [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/>            فهرس كائن EmfPlusPath (القسم 2.2.1.6) للرسم، في جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و63، شاملًا. |
| pen_id | int | r/w | يحصل أو يعيّن معرف القلم<br/>            عدد صحيح غير موقع 32-بت يحدد فهرسًا في جدول كائنات EMF+<br/>            لكائن EmfPlusPen (القسم 2.2.1.7) لاستخدامه في رسم EmfPlusPath.<br/>            يجب أن تكون القيمة بين الصفر و63، شاملًا |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawPath(source) {#EmfPlusDrawPath_source_1}


```
 EmfPlusDrawPath(source) 
```

يُنشئ مثلاً جديدًا من الفئة [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

