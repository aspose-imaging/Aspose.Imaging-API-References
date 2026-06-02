---
title: "فئة EmfPlusEndOfFile"
type: docs
weight: 220
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---

**Summary:** The EmfPlusEndOfFile record specifies the end of EMF+ data in the metafile.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndOfFile

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusEndOfFile(source)](#EmfPlusEndOfFile_source_1) | يُهيئ نسخة جديدة من الفئة [EmfPlusEndOfFile](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 16 بت غير مستخدم. يجب أن يتم تعيين هذا الحقل إلى الصفر<br/>            ويجب تجاهله عند الاستلام. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusEndOfFile(source) {#EmfPlusEndOfFile_source_1}


```
 EmfPlusEndOfFile(source) 
```

يُهيئ نسخة جديدة من الفئة [EmfPlusEndOfFile](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

