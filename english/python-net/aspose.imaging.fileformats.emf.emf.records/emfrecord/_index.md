---
title: EmfRecord Class
type: docs
weight: 940
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/
---

Base class for EMF records<br/>            All EMF records MUST have a length that is a multiple of 4 bytes. This is depicted in the<br/>            generic structures of the preceding EMF record types by including AlignmentPadding fields<br/>            where appropriate at the ends of these structures. The contents of AlignmentPadding fields<br/>            MUST always be ignored. For brevity, these fields are not shown in every individual EMF<br/>            record definition.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRecord

**Inheritance:** MetaObject

**Aspose.Imaging Version:** 23.6

The EmfRecord type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfRecord()](#EmfRecord__0) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [EmfRecord(source)](#EmfRecord_source_1) | Initializes a new instance of the EmfRecord class |
| [EmfRecord(type)](#EmfRecord_type_2) | Initializes a new instance of the EmfRecord class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_4) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfRecord() {#EmfRecord__0}


```
 EmfRecord() 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

### EmfRecord(source) {#EmfRecord_source_1}


```
 EmfRecord(source) 
```

Initializes a new instance of the EmfRecord class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |

### EmfRecord(type) {#EmfRecord_type_2}


```
 EmfRecord(type) 
```

Initializes a new instance of the EmfRecord class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) |  |

### create_from_record(source)  [static] {#create_from_record_source_3}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


### create_from_type(type)  [static] {#create_from_type_type_4}


```
 create_from_type(type) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | The record type. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


