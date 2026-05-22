---
title: "فئة EmfPlusSetCompositingMode"
type: docs
weight: 490
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---

**Summary:** The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetCompositingMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetCompositingMode(source)](#EmfPlusSetCompositingMode_source_1) | إنشاء نسخة جديدة من الفئة [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | الحصول أو تعيين قيمة وضع التجميع، من تعداد CompositingMode (القسم 2.1.1.5). يمكن التعبير عن التجميع كحالة دمج ألفا، والتي يمكن أن تكون مفعلة أو غير مفعلة. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetCompositingMode(source) {#EmfPlusSetCompositingMode_source_1}


```
 EmfPlusSetCompositingMode(source) 
```

إنشاء نسخة جديدة من الفئة [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

