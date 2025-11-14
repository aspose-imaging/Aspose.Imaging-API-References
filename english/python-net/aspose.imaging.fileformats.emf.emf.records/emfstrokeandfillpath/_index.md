---
title: EmfStrokeAndFillPath Class
type: docs
weight: 1420
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/
---

**Summary:** The EMR_STROKEANDFILLPATH record closes any open figures in a path, strokes the outline of the<br/>            path by using the current pen, and fills its interior by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStrokeAndFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStrokeAndFillPath()](#EmfStrokeAndFillPath__1) | Initializes a new instance of the [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) class. |
| [EmfStrokeAndFillPath(source)](#EmfStrokeAndFillPath_source_2) | Initializes a new instance of the [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies<br/>            the bounding rectangle, in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfStrokeAndFillPath() {#EmfStrokeAndFillPath__1}


```
 EmfStrokeAndFillPath() 
```

Initializes a new instance of the [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) class.

### Constructor: EmfStrokeAndFillPath(source) {#EmfStrokeAndFillPath_source_2}


```
 EmfStrokeAndFillPath(source) 
```

Initializes a new instance of the [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) class.

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


