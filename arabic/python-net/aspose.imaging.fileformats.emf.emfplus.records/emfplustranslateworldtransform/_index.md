---
title: "الفئة EmfPlusTranslateWorldTransform"
type: docs
weight: 630
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---

**Summary:** The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTranslateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusTranslateWorldTransform(source)](#EmfPlusTranslateWorldTransform_source_1) | ينشئ مثيلًا جديدًا للفئة [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| dx | float | r/w | الحصول أو تعيين قيمة عائمة 32 بت تحدد المسافة الأفقية. يتم تنفيذ الترجمة<br/>            بإنشاء مصفوفة تحويل عالمية جديدة من حقلي dx و dy. |
| dy | float | r/w | الحصول أو تعيين قيمة عائمة 32 بت تحدد قيمة المسافة العمودية. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| post_multiplied_matrix | bool | r | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix].<br/>            إذا تم تعيينه، يجب أن يتم ضرب مصفوفة التحويل بعديًا (post‑multiplied). إذا لم يتم تعيينه، يجب أن تُضرب مسبقًا (premultiplied). |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusTranslateWorldTransform(source) {#EmfPlusTranslateWorldTransform_source_1}


```
 EmfPlusTranslateWorldTransform(source) 
```

ينشئ مثيلًا جديدًا للفئة [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

