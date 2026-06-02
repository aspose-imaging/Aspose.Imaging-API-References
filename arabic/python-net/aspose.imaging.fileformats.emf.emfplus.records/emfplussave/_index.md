---
title: "فئة EmfPlusSave"
type: docs
weight: 420
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---

**Summary:** The EmfPlusSave record saves the graphics state, identified by a specified index, on a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSave

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSave(source)](#EmfPlusSave_source_1) | يُنشئ مثلاً جديداً من الفئة [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| stack_index | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد مستوىً لربطه بـ<br/>            حالة الرسومات. يمكن استخدام قيمة المستوى بواسطة سجل EmfPlusRestore لاحق (القسم<br/>            2.3.7.4) لاسترجاع حالة الرسومات. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSave(source) {#EmfPlusSave_source_1}


```
 EmfPlusSave(source) 
```

يُنشئ مثلاً جديداً من الفئة [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

