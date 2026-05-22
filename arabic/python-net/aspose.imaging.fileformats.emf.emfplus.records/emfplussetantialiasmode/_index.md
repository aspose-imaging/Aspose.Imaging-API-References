---
title: "فئة EmfPlusSetAntiAliasMode"
type: docs
weight: 450
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---

**Summary:** The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetAntiAliasMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetAntiAliasMode(source)](#EmfPlusSetAntiAliasMode_source_1) | يُنشئ مثيلاً جديدًا من الفئة [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| anti_aliasing | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [anti aliasing].<br/>            إذا تم تعيينه، يجب تنفيذ مضاد التعرج.<br/>            إذا لم يتم تعيينه، يجب عدم تنفيذ مضاد التعرج. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| smoothing_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | يحصل أو يعيّن وضع التنعيم.<br/>            (7 بت): قيمة وضع التنعيم، من تعداد SmoothingMode (القسم 2.1.1.28) |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetAntiAliasMode(source) {#EmfPlusSetAntiAliasMode_source_1}


```
 EmfPlusSetAntiAliasMode(source) 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

