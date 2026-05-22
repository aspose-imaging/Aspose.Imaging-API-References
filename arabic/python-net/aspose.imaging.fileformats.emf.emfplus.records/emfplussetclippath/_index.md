---
title: "فئة EmfPlusSetClipPath"
type: docs
weight: 460
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---

**Summary:** The EmfPlusSetClipPath record combines the current clipping region with a graphics path.<br/>            The new current clipping region is set to the result of the CombineMode operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipPath

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetClipPath(source)](#EmfPlusSetClipPath_source_1) | يُهيئ نسخة جديدة من الفئة [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | الحصول أو تعيين قيمة CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع<br/>            تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | يحصل أو يعيّن فهرس كائن EmfPlusPath (القسم 2.2.1.6) في جدول كائنات EMF+<br/>            . يجب أن تكون القيمة من صفر إلى 63، شاملًا. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetClipPath(source) {#EmfPlusSetClipPath_source_1}


```
 EmfPlusSetClipPath(source) 
```

يُهيئ نسخة جديدة من الفئة [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

