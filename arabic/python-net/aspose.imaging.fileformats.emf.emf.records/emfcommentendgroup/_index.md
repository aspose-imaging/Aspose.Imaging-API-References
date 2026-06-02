---
title: "EmfCommentEndGroup فئة"
type: docs
weight: 200
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/
---

**Summary:** The EMR_COMMENT_ENDGROUP record specifies the end of a group of drawing records.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEndGroup

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCommentEndGroup(source)](#EmfCommentEndGroup_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfCommentEndGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد سجل التعليق هذا <br/>            على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي سلسلة ASCII \"CIDG\"، تحدد <br/>            هذا كسجل EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي <br/>            CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي <br/>            يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding، إذا <br/>            كان موجودًا. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام <br/>            . يجب أن يكون هذا أحد القيم المدرجة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentEndGroup(source) {#EmfCommentEndGroup_source_1}


```
 EmfCommentEndGroup(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfCommentEndGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | المصدر. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | المصدر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | نوع السجل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


