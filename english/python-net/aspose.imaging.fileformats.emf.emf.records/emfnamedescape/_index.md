---
title: EmfNamedEscape Class
type: docs
weight: 660
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---

**Summary:** The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfNamedEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfNamedEscape(source)](#EmfNamedEscape_source_1) | Initializes a new instance of the [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cj_driver | int | r/w | Gets or sets A 32-bit unsigned integer that specifies the number of bytes in the<br/>            DriverName field. This value MUST be an even number. |
| cj_in | int | r/w | Gets or sets A 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| data | System.Byte | r/w | Gets or sets The data to pass to the printer driver. There MUST be cjIn bytes available. |
| driver_name | string | r/w | Gets or sets A string of 16-bit Unicode characters that specifies the name of the<br/>            printer driver that will receive data. This value MUST be cjDriver bytes long, and it MUST be<br/>            terminated with a null character. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to<br/>            execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17). |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfNamedEscape(source) {#EmfNamedEscape_source_1}


```
 EmfNamedEscape(source) 
```

Initializes a new instance of the [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/) class.

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


