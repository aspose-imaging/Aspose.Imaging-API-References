---
title: "فئة EmfDrawEscape"
type: docs
weight: 350
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---

**Summary:** The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will result in drawing being done.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDrawEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfDrawEscape(source)](#EmfDrawEscape_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cj_in | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات التي يتم تمريرها إلى برنامج تشغيل الطابعة. |
| البيانات | System.Byte | r/w | يحصل أو يعيّن البيانات التي يتم تمريرها إلى برنامج تشغيل الطابعة. يجب أن تكون هناك بايتات cjIn متاحة. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد أمر الهروب لبرنامج تشغيل الطابعة <br/>            لتنفيذه. يجب أن يكون هذا أحد القيم في تعداد WMF MetafileEscapes ([MSWMF] القسم 2.1.1.17). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfDrawEscape(source) {#EmfDrawEscape_source_1}


```
 EmfDrawEscape(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/) .

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


