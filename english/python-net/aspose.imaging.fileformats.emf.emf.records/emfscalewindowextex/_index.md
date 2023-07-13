---
title: EmfScaleWindowExtex Class
type: docs
weight: 1020
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---

The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by<br/>            using the ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleWindowExtex

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfScaleWindowExtex type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfScaleWindowExtex(source)](#EmfScaleWindowExtex_source_0) | Initializes a new instance of the [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) class. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex__1) | Initializes a new instance of the [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| x_num | int | r/w | Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. MUST NOT be zero. |
| x_denom | int | r/w | Gets or sets a 32-bit signed integer that specifies the horizontal divisor. MUST NOT be zero. |
| y_num | int | r/w | Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. MUST NOT be zero. |
| y_denom | int | r/w | Gets or sets a 32-bit signed integer that specifies the vertical divisor. MUST NOT be zero. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfScaleWindowExtex(source) {#EmfScaleWindowExtex_source_0}


```
 EmfScaleWindowExtex(source) 
```

Initializes a new instance of the [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex__1}


```
 EmfScaleWindowExtex() 
```

Initializes a new instance of the [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) class.

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


