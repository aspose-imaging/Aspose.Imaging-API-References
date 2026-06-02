---
title: "فئة EmfPlusRotateWorldTransform"
type: docs
weight: 410
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---

**Summary:** The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRotateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusRotateWorldTransform(source)](#EmfPlusRotateWorldTransform_source_1) | يُنشئ مثيلاً جديدًا من الفئة [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| angle | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد زاوية الدوران بالدرجات.<br/>            يتم تنفيذ العملية بإنشاء مصفوفة تحويل جديدة من المخطط التالي<br/>            الرسم البياني:<br/>            ---------------------------------<br/> | sin(Angle) | cos(Angle) | 0 | <br/> | cos(Angle) | sin(Angle) | 0 | <br/>            ---------------------------------<br/>            الشكل 2: مصفوفة تحويل الدوران<br/>            يتم ضرب تحويل الفضاء العالمي الحالي بهذه المصفوفة، وتصبح النتيجة<br/>            تحويل الفضاء العالمي الحالي الجديد. يحدد حقل Flags ترتيب الضرب. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| post_multiplied_matrix | bool | r | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix].<br/>            إذا تم تعيينه، يجب أن يتم ضرب مصفوفة التحويل بعديًا (post‑multiplied). إذا لم يتم تعيينه، يجب أن تُضرب مسبقًا (premultiplied). |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusRotateWorldTransform(source) {#EmfPlusRotateWorldTransform_source_1}


```
 EmfPlusRotateWorldTransform(source) 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

