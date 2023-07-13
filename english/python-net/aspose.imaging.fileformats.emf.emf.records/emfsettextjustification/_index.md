---
title: EmfSetTextJustification Class
type: docs
weight: 1290
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---

The EMR_SETTEXTJUSTIFICATION record specifies the amount of extra space to add to break<br/>            characters for text justification.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextJustification

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetTextJustification type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetTextJustification(source)](#EmfSetTextJustification_source_0) | Initializes a new instance of the [EmfSetTextJustification](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| n_break_extra | int | r/w | Gets or sets a 32-bit signed integer that specifies the total amount of extra space,<br/>            in logical units, to add. |
| n_break_count | int | r/w | Gets or sets a 32-bit signed integer that specifies the number of break characters. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetTextJustification(source) {#EmfSetTextJustification_source_0}


```
 EmfSetTextJustification(source) 
```

Initializes a new instance of the [EmfSetTextJustification](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### create_from_record(source)  [static] {#create_from_record_source_1}


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


### create_from_type(type)  [static] {#create_from_type_type_2}


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


