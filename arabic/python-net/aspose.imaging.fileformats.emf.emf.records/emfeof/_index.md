---
title: "فئة EmfEof"
type: docs
weight: 390
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
| [EmfEof(record)](#EmfEof_record_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | يحصل أو يضبط مخزنًا اختياريًا يحتوي على بيانات لوحة الألوان، والتي لا <br/>            يلزم أن تكون متصلة بالجزء الثابت من سجل EMR_EOF <br/>            . وبالتالي، الحقول في هذا المخزن التي تم تسميتها <br/>            \"UndefinedSpace\" هي اختيارية ويجب تجاهلها. <br/>            يجب أن يكون حجم هذا الحقل مضاعفًا ل 4 بايتات. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| size_last | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يجب أن يكون مساويًا لـ Size ويجب أن يكون الحقل الأخير <br/>            في السجل وبالتالي في ملف الميتا. كائنات LogPaletteEntry، إذا كانت <br/>            موجودة، يجب أن تسبق هذا الحقل. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | السجل. |

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


