---
title: EmfForceUfiMapping Class
type: docs
weight: 510
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/
---

The EMR_FORCEUFIMAPPING record forces the font mapper to match fonts based on their<br/>            UniversalFontId in preference to their LogFont (section 2.2.13) information.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfForceUfiMapping

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfForceUfiMapping type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfForceUfiMapping(source)](#EmfForceUfiMapping_source_0) | Initializes a new instance of the [EmfForceUfiMapping](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| ufi | [EmfUniversalFontId](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/) | r/w | Gets or sets the font id to use, specified as a UniversalFontId (section 2.2.27). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfForceUfiMapping(source) {#EmfForceUfiMapping_source_0}


```
 EmfForceUfiMapping(source) 
```

Initializes a new instance of the [EmfForceUfiMapping](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/) class.

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


