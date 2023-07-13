---
title: EmfSetTextColor Class
type: docs
weight: 1280
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/
---

The EMR_SETTEXTCOLOR record defines the current text color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextColor

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetTextColor type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetTextColor(source)](#EmfSetTextColor_source_0) | Initializes a new instance of the [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) class. |
| [EmfSetTextColor()](#EmfSetTextColor__1) | Initializes a new instance of the [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| argb_32_color | int | r/w | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the text color value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetTextColor(source) {#EmfSetTextColor_source_0}


```
 EmfSetTextColor(source) 
```

Initializes a new instance of the [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetTextColor() {#EmfSetTextColor__1}


```
 EmfSetTextColor() 
```

Initializes a new instance of the [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) class.

### create_from_record(source)  [static] {#create_from_record_source_2}


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


### create_from_type(type)  [static] {#create_from_type_type_3}


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


