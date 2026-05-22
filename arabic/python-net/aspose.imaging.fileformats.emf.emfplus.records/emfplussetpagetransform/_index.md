---
title: "فئة EmfPlusSetPageTransform"
type: docs
weight: 520
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---

**Summary:** The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space<br/>            coordinates to device space coordinates.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPageTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetPageTransform(source)](#EmfPlusSetPageTransform_source_1) | يُنشئ مثيلاً جديدًا للفئة [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| page_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32-بت تحدد معامل التحويل لـ<br/>            إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز. |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | يحصل على وحدة القياس لإحداثيات مساحة الصفحة، من تعداد UnitType<br/>            (القسم 2.1.1.33). يجب ألا تكون هذه القيمة UnitTypeDisplay أو UnitTypeWorld. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetPageTransform(source) {#EmfPlusSetPageTransform_source_1}


```
 EmfPlusSetPageTransform(source) 
```

يُنشئ مثيلاً جديدًا للفئة [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

