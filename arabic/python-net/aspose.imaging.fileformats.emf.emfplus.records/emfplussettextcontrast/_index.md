---
title: "الفئة EmfPlusSetTextContrast"
type: docs
weight: 550
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---

**Summary:** The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTextContrast

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetTextContrast(source)](#EmfPlusSetTextContrast_source_1) | تهيئة نسخة جديدة من الفئة [EmfPlusSetTextContrast](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| text_contrast | int | r/w | الحصول أو تعيين قيمة تصحيح جاما × 1000، التي سيتم تطبيقها على<br/>            عمليات عرض النص اللاحقة. النطاق المسموح به هو 1000 إلى 2200،<br/>            مما يمثل قيم جاما للنص من 1.0 إلى 2.2. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetTextContrast(source) {#EmfPlusSetTextContrast_source_1}


```
 EmfPlusSetTextContrast(source) 
```

تهيئة نسخة جديدة من الفئة [EmfPlusSetTextContrast](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

