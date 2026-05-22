---
title: "EmfPlusSetClipRegion فئة"
type: docs
weight: 480
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---

**Summary:** The EmfPlusSetClipRegion record combines the current clipping region with another graphics region.<br/>            The new current clipping region is set to the result of performing the CombineMode operation on<br/>            the previous current clipping region and the specified EmfPlusRegion object.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRegion

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetClipRegion(source)](#EmfPlusSetClipRegion_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfPlusSetClipRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | الحصول أو تعيين قيمة CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع<br/>            تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | الحصول أو تعيين فهرس كائن EmfPlusRegion (القسم 2.2.1.8) في جدول كائنات EMF+<br/>            . يجب أن تكون القيمة من 0 إلى 63 شاملًا. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetClipRegion(source) {#EmfPlusSetClipRegion_source_1}


```
 EmfPlusSetClipRegion(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfPlusSetClipRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

