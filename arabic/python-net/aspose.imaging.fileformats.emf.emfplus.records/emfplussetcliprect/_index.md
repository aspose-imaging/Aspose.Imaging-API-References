---
title: "الفئة EmfPlusSetClipRect"
type: docs
weight: 470
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---

**Summary:** The EmfPlusSetClipRect record combines the current clipping region with a rectangle.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRect

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetClipRect(source)](#EmfPlusSetClipRect_source_1) | تهيئة نسخة جديدة من الفئة [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| clip_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | الحصول أو تعيين كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المستطيل لاستخدامه<br/>            في عملية CombineMode. |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | الحصول أو تعيين قيمة CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع<br/>            تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetClipRect(source) {#EmfPlusSetClipRect_source_1}


```
 EmfPlusSetClipRect(source) 
```

تهيئة نسخة جديدة من الفئة [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

