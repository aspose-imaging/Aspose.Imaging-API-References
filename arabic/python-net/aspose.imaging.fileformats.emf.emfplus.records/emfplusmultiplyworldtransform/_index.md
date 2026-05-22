---
title: "الفئة EmfPlusMultiplyWorldTransform"
type: docs
weight: 320
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---

**Summary:** The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusMultiplyWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusMultiplyWorldTransform(source)](#EmfPlusMultiplyWorldTransform_source_1) | ينشئ مثيلًا جديدًا للفئة [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | الحصول أو تعيين كائن EmfPlusTransformMatrix (القسم 2.2.2.47) الذي يحدد مصفوفة الضرب. |
| post_multiplied_matrix | bool | r | الحصول على قيمة تشير إلى ما إذا كانت [post multiplied matrix].<br/>            إذا تم تعيينها، يجب أن يتم ضرب مصفوفة التحويل بعديًا. إذا لم يتم تعيينها، يجب أن تُضرب مسبقًا. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusMultiplyWorldTransform(source) {#EmfPlusMultiplyWorldTransform_source_1}


```
 EmfPlusMultiplyWorldTransform(source) 
```

ينشئ مثيلًا جديدًا للفئة [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

