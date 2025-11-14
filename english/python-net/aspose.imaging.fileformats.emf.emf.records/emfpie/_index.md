---
title: EmfPie Class
type: docs
weight: 730
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Initializes a new instance of the [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) class. |
| [EmfPie(source)](#EmfPie_source_2) | Initializes a new instance of the [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which <br/>            specifies the inclusive-inclusive bounding rectangle. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets a 64-bit PointL object that specifies the coordinates, in logical units, of the <br/>            endpoint of the second radial. |
| size | int | r/w | Gets or sets the size of the record |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets a 64-bit WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which <br/>            specifies the coordinates, in logical units, of the endpoint of the first radial. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Initializes a new instance of the [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) class.

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Initializes a new instance of the [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

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


