---
title: "فئة EmfCommentWindowsMetaFile"
type: docs
weight: 240
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

**Summary:** The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCommentWindowsMetaFile(source)](#EmfCommentWindowsMetaFile_source_1) | ينشئ مثيلًا جديدًا من [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) الفئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| checksum | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد مجموع التحقق لهذا السجل. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد سجل التعليق هذا <br/>            على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي سلسلة ASCII \"CIDG\"، تحدد <br/>            هذا كسجل EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي <br/>            CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي <br/>            يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding، إذا <br/>            كان موجودًا. |
| العلامات | int | r/w | يحصل أو يضبط قيمة 32-بت يجب أن تكون 0x00000000 ويجب تجاهلها. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام <br/>            . يجب أن يكون هذا أحد القيم المدرجة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| version | [WmfMetafileVersion](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileversion/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 16-بت يحدد إصدار ملف WMF من حيث دعم الصور النقطية المستقلة عن الجهاز (DIBs)، من تعداد WMF MetafileVersion <br/>            ([MS-WMF] القسم 2.1.1.19). |
| win_metafile | [MetaImage](/imaging/python-net/aspose.imaging.fileformats.emf/metaimage/) | r/w | يحصل أو يضبط مخزنًا يحتوي على ملف WMF. |
| win_metafile_size | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد الحجم، بالبايت، لملف WMF <br/>            في حقل WinMetafile. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentWindowsMetaFile(source) {#EmfCommentWindowsMetaFile_source_1}


```
 EmfCommentWindowsMetaFile(source) 
```

ينشئ مثيلًا جديدًا من [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) الفئة.

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


