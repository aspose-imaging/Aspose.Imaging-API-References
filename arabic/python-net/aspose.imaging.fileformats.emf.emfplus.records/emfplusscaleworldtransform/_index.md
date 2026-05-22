---
title: "فئة EmfPlusScaleWorldTransform"
type: docs
weight: 430
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---

**Summary:** The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusScaleWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusScaleWorldTransform(source)](#EmfPlusScaleWorldTransform_source_1) | يُهيئ نسخة جديدة من الفئة [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| post_multiplied_matrix | bool | r | الحصول على قيمة تشير إلى ما إذا كانت [post multiplied matrix].<br/>            إذا تم تعيينها، يجب أن يتم ضرب مصفوفة التحويل بعديًا. إذا لم يتم تعيينها، يجب أن تُضرب مسبقًا. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| sx | float | r/w | يحصل أو يعيّن قيمة عائمة 32-بت تحدد عامل المقياس الأفقي. يتم تنفيذ التحجيم<br/>            عن طريق إنشاء مصفوفة تحويل جديدة من قيمتي الحقلين Sx و Sy، كما<br/>            هو موضح في الجدول التالي.<br/>            -----------------<br/> | Sx | 0 | 0 | <br/> | 0 | Sx | 0 | <br/>            -----------------<br/>            الشكل 3: مصفوفة تحويل المقياس |
| sy | float | r/w | يحصل أو يعيّن قيمة عائمة 32-بت تحدد عامل المقياس العمودي. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusScaleWorldTransform(source) {#EmfPlusScaleWorldTransform_source_1}


```
 EmfPlusScaleWorldTransform(source) 
```

يُهيئ نسخة جديدة من الفئة [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

