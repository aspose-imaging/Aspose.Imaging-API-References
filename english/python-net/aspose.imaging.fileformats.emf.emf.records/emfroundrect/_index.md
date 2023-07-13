---
title: EmfRoundRect Class
type: docs
weight: 990
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---

The EMR_ROUNDRECT record specifies a rectangle with rounded corners. The rectangle is outlined <br/>            by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRoundRect

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfRoundRect type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfRoundRect(source)](#EmfRoundRect_source_0) | Initializes a new instance of the [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/) class. |
| [EmfRoundRect()](#EmfRoundRect__1) | Initializes a new instance of the [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which <br/>            specifies the inclusive-inclusive rectangle to draw. |
| corner | [Size](/imaging/python-net/aspose.imaging/size) | r/w | Gets or sets a 64-bit WMF SizeL object, specified in [MS-WMF] section 2.2.2.22, which <br/>            specifies the width and height, in logical coordinates, of the ellipse used to draw the rounded corners. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfRoundRect(source) {#EmfRoundRect_source_0}


```
 EmfRoundRect(source) 
```

Initializes a new instance of the [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfRoundRect() {#EmfRoundRect__1}


```
 EmfRoundRect() 
```

Initializes a new instance of the [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/) class.

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


