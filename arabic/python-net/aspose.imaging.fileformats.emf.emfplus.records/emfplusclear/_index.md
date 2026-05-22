---
title: "فئة EmfPlusClear"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---

**Summary:** The EmfPlusClear record clears the output coordinate space and initializes it with a background color and transparency

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClear

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusClear(source)](#EmfPlusClear_source_1) | يُهيئ نسخة جديدة من الفئة [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | يحصل أو يعيّن اللون.<br/>            كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد اللون لطلاء الشاشة. جميع الألوان محددة في [IEC-RGB]، ما لم يُذكر غير ذلك. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusClear(source) {#EmfPlusClear_source_1}


```
 EmfPlusClear(source) 
```

يُهيئ نسخة جديدة من الفئة [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

