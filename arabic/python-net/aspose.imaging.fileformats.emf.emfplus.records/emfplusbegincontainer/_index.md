---
title: "فئة EmfPlusBeginContainer"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---

**Summary:** The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusBeginContainer(source)](#EmfPlusBeginContainer_source_1) | ينشئ مثيلاً جديداً من الفئة [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| dest_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يضبط كائن EmfPlusRectF (section 2.2.2.39) الذي، مع SrcRect، يحدد<br/>a transform for the container. This transformation results in SrcRect when applied to DestRect. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | يحصل على وحدة الصفحة. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يضبط مستطيل EmfPlusRectF الذي، مع DestRect، يحدد تحويلًا<br/>for the container. This transformation results in SrcRect when applied to DestRect. |
| stack_index | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرسًا لربطه بـ<br/>            حاوية حالة الرسومات. يجب الإشارة إلى الفهرس بواسطة سجل EmfPlusEndContainer لاحق (القسم 2.3.7.3) لإغلاق حاوية حالة الرسومات. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusBeginContainer(source) {#EmfPlusBeginContainer_source_1}


```
 EmfPlusBeginContainer(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/) class.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

