---
title: "فئة EmfCommentMultiFormats"
type: docs
weight: 210
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---

**Summary:** The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentMultiFormats

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCommentMultiFormats(source)](#EmfCommentMultiFormats_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| a_formats | [EmfFormat[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/) | r/w | يحصل أو يضبط مصفوفة بطول CountFormats من صيغ الرسومات، المحددة بواسطة <br/>            EmrFormat objects (section 2.2.4)، بترتيب التفضيل |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد سجل التعليق هذا <br/>            على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي سلسلة ASCII \"CIDG\"، تحدد <br/>            هذا كسجل EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي <br/>            CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي <br/>            يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding، إذا <br/>            كان موجودًا. |
| format_data | System.Byte[] | r/w | يحصل أو يضبط مصفوفة بطول متغير من بايتات بيانات الصورة لجميع صيغ الرسومات <br/>            الموجودة في هذا السجل. <br/>            يتم توفير حجم البيانات لكل صورة بواسطة الحقل DataSize في كائن EmrFormat المقابل. وبالتالي، يكون الحجم الكلي لهذا الحقل هو مجموع قيم DataSize في جميع <br/>            كائنات EmrFormat. <br/>            يتم تحديد صيغة الرسومات للبيانات لكل صورة بواسطة الحقل Signature في <br/>            كائن EmrFormat المقابل. |
| output_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يضبط كائن WMF RectL ([MS-WMF] section 2.2.2.19) الذي يحدد <br/>            المستطيل الناتج، بالإحداثيات المنطقية. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام <br/>            . يجب أن يكون هذا أحد القيم المدرجة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentMultiFormats(source) {#EmfCommentMultiFormats_source_1}


```
 EmfCommentMultiFormats(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/).

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


