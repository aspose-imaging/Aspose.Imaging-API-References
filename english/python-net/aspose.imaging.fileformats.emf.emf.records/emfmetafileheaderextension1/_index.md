---
title: EmfMetafileHeaderExtension1 Class
type: docs
weight: 610
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

**Aspose.Imaging Version:** 23.6

The EmfMetafileHeaderExtension1 type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_0) | Initializes a new instance of the EmfMetafileHeaderExtension1 class |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | Initializes a new instance of the EmfMetafileHeaderExtension1 class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Gets or sets a Header object (section 2.2.9), which contains information about the content<br/>            and structure of the metafile |
| emf_header_record_buffer | byte | r/w | Gets or sets an optional array of bytes that contains the remainder of the EMF header record. <br/>            The size of this field MUST be a multiple of 4 bytes |
| emf_description_buffer | byte | r/w | Gets or sets the EMF description buffer<br/>            An optional array of bytes that contains the EMF description string, which is <br/>            not required to be contiguous with the fixed portion of the EmfMetafileHeader <br/>            record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" <br/>            is optional and MUST be ignored. |
| emf_description | string | r/w | Gets or sets the EMF description<br/>            An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. <br/>            Its location in the record and number of characters are specified by the offDescription <br/>            and nDescription fields, respectively, in EmfHeader. If the value of either field <br/>            is zero, no description string is present. |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile. |
| emf_pixel_format_buffer | byte | r/w | Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to<br/>            be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF <br/>            description string. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is <br/>            optional and MUST be ignored |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(record)](#create_from_record_record_2) | Initializes a new instance of the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_header(header)](#create_from_header_header_4) | Initializes a new instance of the [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class. |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_5) | Initializes a new instance of the [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class. |

### EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_0}


```
 EmfMetafileHeaderExtension1(header) 
```

Initializes a new instance of the EmfMetafileHeaderExtension1 class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

Initializes a new instance of the EmfMetafileHeaderExtension1 class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) |  |

### create_from_record(record)  [static] {#create_from_record_record_2}


```
 create_from_record(record) 
```

Initializes a new instance of the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |


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


### create_from_header(header)  [static] {#create_from_header_header_4}


```
 create_from_header(header) 
```

Initializes a new instance of the [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | The header. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) |  |


### create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_5}


```
 create_from_header_extension1(header) 
```

Initializes a new instance of the [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | The header. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) |  |


