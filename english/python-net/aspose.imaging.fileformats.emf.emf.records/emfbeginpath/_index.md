---
title: EmfBeginPath Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---

**Summary:** This record opens a path bracket in the current playback device context.<br/>            After a path bracket is open, an application can begin processing records to define<br/>            the points that lie in the path.An application MUST close an open path bracket by<br/>            processing the EMR_ENDPATH record.<br/>            When an application processes the EMR_BEGINPATH record, all previous paths<br/>            MUST be discarded from the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBeginPath

**Inheritance:** EmfPathBracketRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfBeginPath()](#EmfBeginPath__1) | Initializes a new instance of the [EmfBeginPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfBeginPath() {#EmfBeginPath__1}


```
 EmfBeginPath() 
```

Initializes a new instance of the [EmfBeginPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/) class.

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


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
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


