---
title: EmfExtEscape Class
type: docs
weight: 430
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/
---

The EMR_EXTESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will not result in drawing being done.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtEscape

**Inheritance:** EmfEscapeRecordType

**Aspose.Imaging Version:** 23.6

The EmfExtEscape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfExtEscape(source)](#EmfExtEscape_source_0) | Initializes a new instance of the [EmfExtEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to<br/>            execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17). |
| cj_in | int | r/w | Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| data | byte | r/w | Gets or sets the data to pass to the printer driver. There MUST be cjIn bytes available. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfExtEscape(source) {#EmfExtEscape_source_0}


```
 EmfExtEscape(source) 
```

Initializes a new instance of the [EmfExtEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/) class.

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


