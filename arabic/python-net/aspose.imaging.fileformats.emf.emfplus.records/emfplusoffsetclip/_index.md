---
title: "EmfPlusOffsetClip فئة"
type: docs
weight: 350
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---

**Summary:** The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space.<br/>            The new current clipping region is set to the result of the translation transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusOffsetClip

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusOffsetClip(source)](#EmfPlusOffsetClip_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| dx | float | r/w | يحصل أو يعيّن قيمة عائمة 32 بت تحدد الإزاحة الأفقية للترجمة. |
| dy | float | r/w | يحصل أو يعيّن قيمة عائمة 32 بت تحدد الإزاحة العمودية للترجمة. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusOffsetClip(source) {#EmfPlusOffsetClip_source_1}


```
 EmfPlusOffsetClip(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

