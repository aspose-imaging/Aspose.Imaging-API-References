---
title: "فئة EmfCommentBeginGroup"
type: docs
weight: 170
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---

**Summary:** The EMR_COMMENT_BEGINGROUP record specifies the beginning of a group of drawing records.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentBeginGroup

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCommentBeginGroup(source)](#EmfCommentBeginGroup_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfCommentBeginGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد سجل التعليق هذا <br/>            على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي سلسلة ASCII \"CIDG\"، تحدد <br/>            هذا كسجل EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي <br/>            CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي <br/>            يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding، إذا <br/>            كان موجودًا. |
| الوصف | string | r/w | يحصل أو يعيّن سلسلة Unicode اختيارية منتهية بصفر تصف مجموعة السجلات هذه. |
| n_description | int | r/w | يحصل أو يعيّن عدد أحرف Unicode في سلسلة الوصف الاختيارية التي تلي ذلك. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام <br/>            . يجب أن يكون هذا أحد القيم المدرجة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMW RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد<br/>            المستطيل الناتج بالإحداثيات المنطقية. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentBeginGroup(source) {#EmfCommentBeginGroup_source_1}


```
 EmfCommentBeginGroup(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfCommentBeginGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/) .

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


