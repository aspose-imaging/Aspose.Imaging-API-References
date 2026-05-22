---
title: "الفئة EmfPlusEndContainer"
type: docs
weight: 210
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---

**Summary:** The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusEndContainer(source)](#EmfPlusEndContainer_source_1) | تهيئة نسخة جديدة من الفئة [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| stack_index | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد فهرس حاوية حالة الرسومات<br/>            يجب أن يتطابق الفهرس مع القيمة المرتبطة بحاوية حالة الرسومات<br/>            التي تم فتحها بواسطة سجل EmfPlusBeginContainer السابق (القسم 2.3.7.1) أو<br/>            سجل EmfPlusBeginContainerNoParams (القسم 2.3.7.2). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusEndContainer(source) {#EmfPlusEndContainer_source_1}


```
 EmfPlusEndContainer(source) 
```

تهيئة نسخة جديدة من الفئة [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

