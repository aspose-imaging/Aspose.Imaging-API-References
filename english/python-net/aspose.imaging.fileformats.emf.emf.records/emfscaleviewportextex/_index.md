---
title: EmfScaleViewportExtex Class
type: docs
weight: 1010
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---

The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the<br/>            ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleViewportExtex

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfScaleViewportExtex type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfScaleViewportExtex(source)](#EmfScaleViewportExtex_source_0) | Initializes a new instance of the [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) class. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex__1) | Initializes a new instance of the [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| x_num | int | r/w | Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. Cannot be zero. |
| x_denom | int | r/w | Gets or sets a 32-bit signed integer that specifies the horizontal divisor. Cannot be zero. |
| y_num | int | r/w | Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. Cannot be zero. |
| y_denom | int | r/w | Gets or sets a 32-bit signed integer that specifies the vertical divisor. Cannot be zero. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfScaleViewportExtex(source) {#EmfScaleViewportExtex_source_0}


```
 EmfScaleViewportExtex(source) 
```

Initializes a new instance of the [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex__1}


```
 EmfScaleViewportExtex() 
```

Initializes a new instance of the [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) class.

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


