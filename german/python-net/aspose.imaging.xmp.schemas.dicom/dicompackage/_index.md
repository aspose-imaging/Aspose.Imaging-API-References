---
title: "DicomPackage Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Initialisiert eine neue Instanz der [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| count | int | r | Liest die XMP‑Schlüsselanzahl. |
| namespace_uri | string | r | Gibt den Namespace-URI zurück. |
| prefix | string | r | Gibt das Präfix zurück. |
| xml_namespace | string | r | Gibt den XML-Namespace zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Fügt den Wert dem angegebenen Schlüssel hinzu. |
| [add_value(key, value)](#add_value_key_value_2) | Fügt den Wert dem angegebenen Schlüssel hinzu. |
| clear() | Löscht diese Instanz. |
| [contains_key(key)](#contains_key_key_3) | Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält. |
| [get_prop_value(key)](#get_prop_value_key_4) | Gibt das Objekt mit dem angegebenen Schlüssel zurück. |
| [get_xml_value()](#get_xml_value__5) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [remove(key)](#remove_key_6) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | Setzt die Geräteinstitution. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | Setzt den Gerätehersteller. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | Setzt das Geburtsdatum des Patienten. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | Setzt die Patienten-ID. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | Setzt den Farbmodus. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | Setzt das Geschlecht des Patienten. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | Setzt das Serien-Datum und die Serien-Uhrzeit. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | Setzt die Serienbeschreibung. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | Setzt die Modalität der Dokumentenserie. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | Setzt die Seriennummer. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | Setzt das Studien-Datum und die Studien-Uhrzeit. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | Setzt die Studienbeschreibung. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | Setzt die Studien-ID. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | Setzt den Studienarzt. |
| [set_value(key, value)](#set_value_key_value_22) | Setzt den Wert. |
| [set_value(key, value)](#set_value_key_value_23) | Setzt den Wert. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | Setzt den XMP‑Typwert. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | Gibt den Wert anhand des _key_ zurück. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Initialisiert eine neue Instanz der [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) Klasse.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Fügt den Wert dem angegebenen Schlüssel hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | string | Der Wert, zu dem hinzugefügt wird. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Fügt den Wert dem angegebenen Schlüssel hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | System.Object | Der Wert, zu dem hinzugefügt wird. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der zu prüfende Schlüssel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | **True** wenn das  den angegebenen Schlüssel enthält; andernfalls, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Gibt das Objekt mit dem angegebenen Schlüssel zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der Schlüssel, der den Wert identifiziert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object | Gibt das Objekt mit dem angegebenen Schlüssel zurück. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den XMP-Wert zurück, konvertiert in die XML-Darstellung. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Entfernt den Wert mit dem angegebenen Schlüssel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem entfernten Wert identifiziert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Gibt true zurück, wenn der Wert mit dem angegebenen Schlüssel entfernt wurde. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

Setzt die Geräteinstitution.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| equipment_institution | string | Die Geräteinstitution. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Setzt den Gerätehersteller.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| equipment_manufacturer | string | Der Gerätehersteller. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

Setzt das Geburtsdatum des Patienten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| patient_birth_date | string | Das Geburtsdatum des Patienten. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

Setzt die Patienten-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| patient_id | string | Die Patienten-ID. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

Setzt den Farbmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| patient_name | string | Der Name des Patienten. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

Setzt das Geschlecht des Patienten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| patient_sex | string | Das Geschlecht des Patienten. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der Schlüssel, der den Wert identifiziert. |
| Wert | System.Object | Das Objekt mit dem angegebenen Schlüssel. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

Setzt das Serien-Datum und die Serien-Uhrzeit.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| series_date_time | string | Das Datum und die Uhrzeit der Serie. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

Setzt die Serienbeschreibung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| series_description | string | Die Serienbeschreibung. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

Setzt die Modalität der Dokumentenserie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| series_modality | string | Die Modalität der Serie. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

Setzt die Seriennummer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| series_number | string | Die Seriennummer. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

Setzt das Studien-Datum und die Studien-Uhrzeit.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| study_date_time | string | Das studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

Setzt die Studienbeschreibung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| study_description | string | Die Studienbeschreibung. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

Setzt die Studien-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| study_id | string | Die Studien-ID. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

Setzt den Studienarzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| study_physician | string | Der Studienarzt. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP‑Typwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

Gibt den Wert anhand des _key_ zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der XMP-Elementschlüssel. |
| Wert | System.Object | Der XMP-Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | **True**, wenn das  den _key_ enthält; andernfalls **False**. |


