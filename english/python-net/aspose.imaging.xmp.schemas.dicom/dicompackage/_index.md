---
title: DicomPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.Imaging Version:** 23.6

The DicomPackage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [DicomPackage()](#DicomPackage__0) | Initializes a new instance of the [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| xml_namespace | string | r | Gets the XML namespace. |
| prefix | string | r | Gets the prefix. |
| namespace_uri | string | r | Gets the namespace URI. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains_key(key)](#contains_key_key_1) | Determines whether the specified key contains key. |
| [get_prop_value(key)](#get_prop_value_key_2) | Gets the object with the specified key. |
| [set_prop_value(key, value)](#set_prop_value_key_value_3) | Gets or sets the object with the specified key. |
| [add_value(key, value)](#add_value_key_value_4) | Adds the value. |
| [remove(key)](#remove_key_5) | Remove the value with the specified key. |
| clear() | Clears this instance. |
| [set_value(key, value)](#set_value_key_value_6) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_7) | Sets the XMP type value. |
| [get_xml_value()](#get_xml_value__8) | Converts XMP value to the XML representation. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_9) | Sets the equipment institution. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_10) | Sets the equipment manufacturer. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_11) | Sets the patient's birth date. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_12) | Sets the patient's ID. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_13) | Sets the color mode. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_14) | Sets the patient's sex. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_15) | Sets the series date time. |
| [set_series_description(series_description)](#set_series_description_series_description_16) | Sets series description. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_17) | Sets the document series modality. |
| [set_series_number(series_number)](#set_series_number_series_number_18) | Sets the series number. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_19) | Sets the study DateTime. |
| [set_study_description(study_description)](#set_study_description_study_description_20) | Sets the study description. |
| [set_study_id(study_id)](#set_study_id_study_id_21) | Sets the study ID. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_22) | Sets the study physician. |

### DicomPackage() {#DicomPackage__0}


```
 DicomPackage() 
```

Initializes a new instance of the [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) class.

### contains_key(key) {#contains_key_key_1}


```
 contains_key(key) 
```

Determines whether the specified key contains key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key to be checked. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the specified key contains key. |


### get_prop_value(key) {#get_prop_value_key_2}


```
 get_prop_value(key) 
```

Gets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |

**Returns**

| Type | Description |
| :- | :- |
| object | Returns the object with the specified key. |


### set_prop_value(key, value) {#set_prop_value_key_value_3}


```
 set_prop_value(key, value) 
```

Gets or sets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | object | The object with the specified key. |

### add_value(key, value) {#add_value_key_value_4}


```
 add_value(key, value) 
```

Adds the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The value to add to. |

### remove(key) {#remove_key_5}


```
 remove(key) 
```

Remove the value with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with removed value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the value with the specified key was removed. |


### set_value(key, value) {#set_value_key_value_6}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue) | The value to add to. |

### set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_7}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### get_xml_value() {#get_xml_value__8}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_9}


```
 set_equipment_institution(equipment_institution) 
```

Sets the equipment institution.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| equipment_institution | string | The equipment institution. |

### set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_10}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Sets the equipment manufacturer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| equipment_manufacturer | string | The equipment manufacturer. |

### set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_11}


```
 set_patient_birth_date(patient_birth_date) 
```

Sets the patient's birth date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_birth_date | string | The patient's birth date. |

### set_patient_id(patient_id) {#set_patient_id_patient_id_12}


```
 set_patient_id(patient_id) 
```

Sets the patient's ID.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_id | string | The patient's ID. |

### set_patient_name(patient_name) {#set_patient_name_patient_name_13}


```
 set_patient_name(patient_name) 
```

Sets the color mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_name | string | The patient's name. |

### set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_14}


```
 set_patient_sex(patient_sex) 
```

Sets the patient's sex.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_sex | string | The patient's sex. |

### set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_15}


```
 set_series_date_time(series_date_time) 
```

Sets the series date time.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_date_time | string | The series date time. |

### set_series_description(series_description) {#set_series_description_series_description_16}


```
 set_series_description(series_description) 
```

Sets series description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_description | string | The series description. |

### set_series_modality(series_modality) {#set_series_modality_series_modality_17}


```
 set_series_modality(series_modality) 
```

Sets the document series modality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_modality | string | The series modality. |

### set_series_number(series_number) {#set_series_number_series_number_18}


```
 set_series_number(series_number) 
```

Sets the series number.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_number | string | The series number. |

### set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_19}


```
 set_study_date_time(study_date_time) 
```

Sets the study DateTime.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_date_time | string | The studyDateTime. |

### set_study_description(study_description) {#set_study_description_study_description_20}


```
 set_study_description(study_description) 
```

Sets the study description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_description | string | The study description. |

### set_study_id(study_id) {#set_study_id_study_id_21}


```
 set_study_id(study_id) 
```

Sets the study ID.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_id | string | The study ID. |

### set_study_physician(study_physician) {#set_study_physician_study_physician_22}


```
 set_study_physician(study_physician) 
```

Sets the study physician.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_physician | string | The study physician. |

