---
title: EmfRectangle Class
type: docs
weight: 950
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---

The EMR_RECTANGLE record draws a rectangle. The rectangle is outlined by using the current pen<br/>            and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRectangle

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfRectangle type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfRectangle(source)](#EmfRectangle_source_0) | Initializes a new instance of the [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) class. |
| [EmfRectangle()](#EmfRectangle__1) | Initializes a new instance of the [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which <br/>            specifies the inclusive-inclusive rectangle to draw. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfRectangle(source) {#EmfRectangle_source_0}


```
 EmfRectangle(source) 
```

Initializes a new instance of the [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfRectangle() {#EmfRectangle__1}


```
 EmfRectangle() 
```

Initializes a new instance of the [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) class.

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


