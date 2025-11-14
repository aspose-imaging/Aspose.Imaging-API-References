---
title: EmfColorMatchToTargetW Class
type: docs
weight: 150
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---

**Summary:** The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color<br/>            profile that is specified in a file with a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorMatchToTargetW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfColorMatchToTargetW(source)](#EmfColorMatchToTargetW_source_1) | Initializes a new instance of the [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size of the raw data of the target<br/>            color profile, if it is contained in the Data field. |
| cb_name | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode<br/>            UTF16-LE name of the desired color profile. |
| data | System.Byte | r/w | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE<br/>            name and raw data of the desired color profile. |
| dw_action | [EmfColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/) | r/w | Gets or sets a 32-bit unsigned integer that specifies a value from the ColorSpace<br/>            enumeration (section 2.1.7). |
| dw_flags | [EmfColorMatchToTarget](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolormatchtotarget/) | r/w | Gets or sets a 32-bit unsigned integer that specifies a value from the<br/>            ColorMatchToTarget enumeration (section 2.1.6). |
| name | string | r | Gets the name |
| raw_data | System.Byte | r | Gets the raw data |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfColorMatchToTargetW(source) {#EmfColorMatchToTargetW_source_1}


```
 EmfColorMatchToTargetW(source) 
```

Initializes a new instance of the [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/) class.

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


