---
title: EmfMetafileHeaderExtension2 Class
type: docs
weight: 620
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/
---

**Summary:** The EmfMetafileHeaderExtension2 record is the header record used in the second extension to EMF<br/>            metafiles. Following the EmfHeaderExtension2 field, the remaining fields are optional and<br/>            can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension2

**Inheritance:** EmfMetafileHeaderExtension1

**Aspose.Imaging Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMetafileHeaderExtension2(header)](#EmfMetafileHeaderExtension2_header_1) | Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class. |
| [EmfMetafileHeaderExtension2(header)](#EmfMetafileHeaderExtension2_header_2) | Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Gets or sets the EMF description<br/>            An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. <br/>            Its location in the record and number of characters are specified by the offDescription <br/>            and nDescription fields, respectively, in EmfHeader. If the value of either field <br/>            is zero, no description string is present. |
| emf_description_buffer | byte | r/w | Gets or sets the EMF description buffer<br/>            An optional array of bytes that contains the EMF description string, which is <br/>            not required to be contiguous with the fixed portion of the EmfMetafileHeader <br/>            record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" <br/>            is optional and MUST be ignored. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Gets or sets a Header object (section 2.2.9), which contains information about the content<br/>            and structure of the metafile |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile. |
| emf_header_extension2 | [EmfHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/) | r/w | Gets or sets a HeaderExtension2 object, which specifies additional information about the image in the metafile |
| emf_header_record_buffer | byte | r/w | Gets or sets an optional array of bytes that contains the remainder of the EMF header record. <br/>            The size of this field MUST be a multiple of 4 bytes |
| emf_pixel_format_buffer | byte | r/w | Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to<br/>            be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF <br/>            description string. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is <br/>            optional and MUST be ignored |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class. |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class. |
| [create_from_header_extension2(header)](#create_from_header_extension2_header_3) | Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class. |
| [create_from_record(record)](#create_from_record_record_4) | Initializes a new instance of the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) class. |
| [create_from_type(type)](#create_from_type_type_5) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfMetafileHeaderExtension2(header) {#EmfMetafileHeaderExtension2_header_1}


```
 EmfMetafileHeaderExtension2(header) 
```

Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | The header. |

### Constructor: EmfMetafileHeaderExtension2(header) {#EmfMetafileHeaderExtension2_header_2}


```
 EmfMetafileHeaderExtension2(header) 
```

Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2) | The header. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | The header. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | The header. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2) |  |


### Method: create_from_header_extension2(header)  [static] {#create_from_header_extension2_header_3}


```
 create_from_header_extension2(header) 
```

Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2) | The header. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_4}


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


### Method: create_from_type(type)  [static] {#create_from_type_type_5}


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


