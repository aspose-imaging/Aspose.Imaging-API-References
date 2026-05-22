---
title: "فئة EmfPlusComment"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---

**Summary:** The EmfPlusComment record specifies arbitrary private data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusComment

**Inheritance:** EmfPlusRecord

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusComment(source)](#EmfPlusComment_source_1) | يُنشئ مثلاً جديدًا من الفئة [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 16 بت غير مستخدم. يجب أن يتم تعيين هذا الحقل إلى الصفر<br/>            ويجب تجاهله عند الاستلام. |
| private_data | System.Byte | r/w | يحصل أو يعيّن مصفوفة بايت بطول DataSize من البيانات الخاصة.<br/>            بايتات من بيانات السجل المحددة التي تلي ذلك. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusComment(source) {#EmfPlusComment_source_1}


```
 EmfPlusComment(source) 
```

يُنشئ مثلاً جديدًا من الفئة [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

