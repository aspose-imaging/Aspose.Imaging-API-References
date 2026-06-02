---
title: "EmfPlusRestore فئة"
type: docs
weight: 400
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---

**Summary:** The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRestore

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusRestore(source)](#EmfPlusRestore_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| stack_index | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد المستوى المرتبط بحالة رسومية.<br/>            تم تعيين قيمة المستوى لحالة الرسوم بواسطة سجل EmfPlusSave السابق (القسم 2.3.7.5). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusRestore(source) {#EmfPlusRestore_source_1}


```
 EmfPlusRestore(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

