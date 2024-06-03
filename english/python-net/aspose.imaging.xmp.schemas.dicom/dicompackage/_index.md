---
title: DicomPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.Imaging Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Initializes a new instance of the [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Gets the namespace URI. |
| prefix | string | r | Gets the prefix. |
| xml_namespace | string | r | Gets the XML namespace. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Adds the value. |
| clear() | Clears this instance. |
| [contains_key(key)](#contains_key_key_2) | Determines whether the specified key contains key. |
| [get_prop_value(key)](#get_prop_value_key_3) | Gets the object with the specified key. |
| [get_xml_value()](#get_xml_value__4) | Converts XMP value to the XML representation. |
| [remove(key)](#remove_key_5) | Remove the value with the specified key. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_6) | Sets the equipment institution. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_7) | Sets the equipment manufacturer. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_8) | Sets the patient's birth date. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_9) | Sets the patient's ID. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_10) | Sets the color mode. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_11) | Sets the patient's sex. |
| [set_prop_value(key, value)](#set_prop_value_key_value_12) | Gets or sets the object with the specified key. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_13) | Sets the series date time. |
| [set_series_description(series_description)](#set_series_description_series_description_14) | Sets series description. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_15) | Sets the document series modality. |
| [set_series_number(series_number)](#set_series_number_series_number_16) | Sets the series number. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_17) | Sets the study DateTime. |
| [set_study_description(study_description)](#set_study_description_study_description_18) | Sets the study description. |
| [set_study_id(study_id)](#set_study_id_study_id_19) | Sets the study ID. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_20) | Sets the study physician. |
| [set_value(key, value)](#set_value_key_value_21) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_22) | Sets the XMP type value. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Initializes a new instance of the [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) class.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Adds the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The value to add to. |

### Method: contains_key(key) {#contains_key_key_2}


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


### Method: get_prop_value(key) {#get_prop_value_key_3}


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


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### Method: remove(key) {#remove_key_5}


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


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_6}


```
 set_equipment_institution(equipment_institution) 
```

Sets the equipment institution.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| equipment_institution | string | The equipment institution. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_7}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Sets the equipment manufacturer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| equipment_manufacturer | string | The equipment manufacturer. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_8}


```
 set_patient_birth_date(patient_birth_date) 
```

Sets the patient's birth date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_birth_date | string | The patient's birth date. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_9}


```
 set_patient_id(patient_id) 
```

Sets the patient's ID.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_id | string | The patient's ID. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_10}


```
 set_patient_name(patient_name) 
```

Sets the color mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_name | string | The patient's name. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_11}


```
 set_patient_sex(patient_sex) 
```

Sets the patient's sex.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| patient_sex | string | The patient's sex. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_12}


```
 set_prop_value(key, value) 
```

Gets or sets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | object | The object with the specified key. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_13}


```
 set_series_date_time(series_date_time) 
```

Sets the series date time.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_date_time | string | The series date time. |

### Method: set_series_description(series_description) {#set_series_description_series_description_14}


```
 set_series_description(series_description) 
```

Sets series description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_description | string | The series description. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_15}


```
 set_series_modality(series_modality) 
```

Sets the document series modality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_modality | string | The series modality. |

### Method: set_series_number(series_number) {#set_series_number_series_number_16}


```
 set_series_number(series_number) 
```

Sets the series number.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| series_number | string | The series number. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_17}


```
 set_study_date_time(study_date_time) 
```

Sets the study DateTime.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_date_time | string | The studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_18}


```
 set_study_description(study_description) 
```

Sets the study description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_description | string | The study description. |

### Method: set_study_id(study_id) {#set_study_id_study_id_19}


```
 set_study_id(study_id) 
```

Sets the study ID.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_id | string | The study ID. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_20}


```
 set_study_physician(study_physician) 
```

Sets the study physician.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| study_physician | string | The study physician. |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_22}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

