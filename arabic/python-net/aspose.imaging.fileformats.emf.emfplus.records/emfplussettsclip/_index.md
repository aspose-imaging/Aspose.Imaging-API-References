---
title: "فئة EmfPlusSetTsClip"
type: docs
weight: 570
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---

**Summary:** The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsClip

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetTsClip(source)](#EmfPlusSetTsClip_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| compressed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) مضغوطًا.<br/>            يحدد هذا البت تنسيق بيانات المستطيلات في حقل rects. إذا تم التعيين، يُعرّف كل مستطيل بـ 4 بايتات. إذا لم يتم التعيين، يُعرّف كل مستطيل بـ 8 بايتات. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| num_rects | int | r | يحصل على عدد المستطيلات.<br/>            يحدد هذا الحقل عدد المستطيلات المعرفة في حقل rect. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. تنسيق<br/>            هذه البيانات يُحدد بواسطة البت C في حقل العلامات. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSetTsClip(source) {#EmfPlusSetTsClip_source_1}


```
 EmfPlusSetTsClip(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

