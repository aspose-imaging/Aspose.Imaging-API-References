---
title: "DicomPackage-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Initierar en ny instans av klassen [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Hämtar antalet XMP-nycklar. |
| namespace_uri | string | r | Hämtar namnrymdens URI. |
| prefix | string | r | Hämtar prefixet. |
| xml_namespace | string | r | Hämtar XML-namnrymden. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Lägger till värdet i den angivna nyckeln. |
| [add_value(key, value)](#add_value_key_value_2) | Lägger till värdet i den angivna nyckeln. |
| clear() | Rensar detta objekt. |
| [contains_key(key)](#contains_key_key_3) | Bestämmer om denna samling har den angivna nyckeln. |
| [get_prop_value(key)](#get_prop_value_key_4) | Hämtar objektet med den angivna nyckeln. |
| [get_xml_value()](#get_xml_value__5) | Konverterar XMP‑värde till XML‑representationen. |
| [remove(key)](#remove_key_6) | Tar bort värdet med den angivna nyckeln. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | Ställer in utrustningens institution. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | Ställer in utrustningens tillverkare. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | Ställer in patientens födelsedatum. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | Ställer in patientens ID. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | Ställer in färgläget. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | Ställer in patientens kön. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Hämtar eller anger objektet med den angivna nyckeln. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | Ställer in seriens datum och tid. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | Ställer in seriebeskrivning. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | Ställer in dokumentseriens modalitet. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | Ställer in serienumret. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | Ställer in studiens datum och tid. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | Ställer in studiedeskrivning. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | Ställer in studiens ID. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | Ställer in studiens läkare. |
| [set_value(key, value)](#set_value_key_value_22) | Anger värdet. |
| [set_value(key, value)](#set_value_key_value_23) | Anger värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | Anger XMP‑typvärdet. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | Hämtar värdet med _key_. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Initierar en ny instans av klassen [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Lägger till värdet i den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | string | Värdet att lägga till. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Lägger till värdet i den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | System.Object | Värdet att lägga till. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Bestämmer om denna samling har den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som ska kontrolleras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | **True** om den  innehåller den angivna nyckeln; annars, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Hämtar objektet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som identifierar värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Object | Returnerar objektet med den angivna nyckeln. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Konverterar XMP‑värde till XML‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar XMP‑värdet konverterat till XML‑representationen. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Tar bort värdet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med borttaget värde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om värdet med den angivna nyckeln togs bort. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

Ställer in utrustningens institution.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| equipment_institution | string | Utrustningens institution. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Ställer in utrustningens tillverkare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| equipment_manufacturer | string | Utrustningens tillverkare. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

Ställer in patientens födelsedatum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| patient_birth_date | string | Patientens födelsedatum. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

Ställer in patientens ID.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| patient_id | string | Patientens ID. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

Ställer in färgläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| patient_name | string | Patientens namn. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

Ställer in patientens kön.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| patient_sex | string | Patientens kön. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Hämtar eller anger objektet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som identifierar värdet. |
| värde | System.Object | Objektet med den angivna nyckeln. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

Ställer in seriens datum och tid.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| series_date_time | string | Seriens datum och tid. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

Ställer in seriebeskrivning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| series_description | string | Seriens beskrivning. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

Ställer in dokumentseriens modalitet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| series_modality | string | Seriens modalitet. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

Ställer in serienumret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| series_number | string | Seriens nummer. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

Ställer in studiens datum och tid.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| study_date_time | string | Den studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

Ställer in studiedeskrivning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| study_description | string | Studiebeskrivningen. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

Ställer in studiens ID.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| study_id | string | Studie-ID. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

Ställer in studiens läkare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| study_physician | string | Studieläkaren. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Värdet att lägga till. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

Anger XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Värdet att sätta till. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

Hämtar värdet med _key_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | XMP‑elementnyckeln. |
| värde | System.Object | XMP‑värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | **True**, om den innehåller _key_; annars **False**. |


