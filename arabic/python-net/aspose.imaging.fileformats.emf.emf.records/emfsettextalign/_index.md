---
title: "فئة EmfSetTextAlign"
type: docs
weight: 1300
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---

**Summary:** The EMR_SETTEXTALIGN record specifies text alignment.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextAlign

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetTextAlign()](#EmfSetTextAlign__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) . |
| [EmfSetTextAlign(source)](#EmfSetTextAlign_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| text_alignment_mode | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد محاذاة النص عن طريق<br/>            استخدام قناع من أعلام محاذاة النص. هذه إما [WmfTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/)<br/>            ([MS-WMF] القسم 2.1.2.3) للنص ذو الخط الأساسي الأفقي، أو [WmfVerticalTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/)<br/>            ([MS-WMF] القسم 2.1.2.4) للنص ذو الخط الأساسي العمودي<br/>            . يمكن اختيار قيمة واحدة فقط من تلك التي تؤثر على المحاذاة الأفقية والعمودية. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetTextAlign() {#EmfSetTextAlign__1}


```
 EmfSetTextAlign() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) .

### Constructor: EmfSetTextAlign(source) {#EmfSetTextAlign_source_2}


```
 EmfSetTextAlign(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) .

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


