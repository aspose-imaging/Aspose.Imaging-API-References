---
title: "فئة EmfPlusBeginContainerNoParams"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---

**Summary:** The EmfPlusBeginContainerNoParams record opens a new graphics state container.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainerNoParams

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusBeginContainerNoParams(source)](#EmfPlusBeginContainerNoParams_source_1) | يُنشئ مثلاً جديداً من الفئة [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| stack_index | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرسًا لربطه بـ<br/>            حاوية حالة الرسومات. يجب الإشارة إلى الفهرس بواسطة سجل EmfPlusEndContainer لاحق (القسم 2.3.7.3) لإغلاق حاوية حالة الرسومات. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusBeginContainerNoParams(source) {#EmfPlusBeginContainerNoParams_source_1}


```
 EmfPlusBeginContainerNoParams(source) 
```

يُنشئ مثلاً جديداً من الفئة [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

