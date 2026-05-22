---
title: "فئة EmfSetLinkedUfis"
type: docs
weight: 1200
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/
---

**Summary:** The EMR_SETLINKEDUFIS record sets the UniversalFontIds (section 2.2.27) of the linked fonts to<br/>            use during character lookup.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetLinkedUfis

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetLinkedUfis(source)](#EmfSetLinkedUfis_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfSetLinkedUfis](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| ufis | [EmfUniversalFontId[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/) | r/w | يحصل أو يعيّن مصفوفة من عناصر uNumLinkedUFI من نوع UniversalFontId، والتي تحدد<br/>            معرفات الخطوط المرتبطة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetLinkedUfis(source) {#EmfSetLinkedUfis_source_1}


```
 EmfSetLinkedUfis(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfSetLinkedUfis](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/).

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


