---
title: "DicomPackage Classe"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Inizializza una nuova istanza della classe [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| count | int | r | Ottiene il conteggio delle chiavi XMP. |
| namespace_uri | string | r | Restituisce l'URI dello spazio dei nomi. |
| prefix | string | r | Restituisce il prefisso. |
| xml_namespace | string | r | Restituisce lo spazio dei nomi XML. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Aggiunge il valore alla chiave specificata. |
| [add_value(key, value)](#add_value_key_value_2) | Aggiunge il valore alla chiave specificata. |
| clear() | Cancella questa istanza. |
| [contains_key(key)](#contains_key_key_3) | Determina se questa collezione contiene la chiave specificata. |
| [get_prop_value(key)](#get_prop_value_key_4) | Restituisce l'oggetto con la chiave specificata. |
| [get_xml_value()](#get_xml_value__5) | Converte il valore XMP nella rappresentazione XML. |
| [remove(key)](#remove_key_6) | Rimuove il valore con la chiave specificata. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | Imposta l'istituzione dell'apparecchiatura. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | Imposta il produttore dell'apparecchiatura. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | Imposta la data di nascita del paziente. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | Imposta l'ID del paziente. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | Imposta la modalità colore. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | Imposta il sesso del paziente. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Restituisce o imposta l'oggetto con la chiave specificata. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | Imposta la data e ora della serie. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | Imposta la descrizione della serie. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | Imposta la modalità della serie di documenti. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | Imposta il numero della serie. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | Imposta la data e ora dello studio. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | Imposta la descrizione dello studio. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | Imposta l'ID dello studio. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | Imposta il medico dello studio. |
| [set_value(key, value)](#set_value_key_value_22) | Imposta il valore. |
| [set_value(key, value)](#set_value_key_value_23) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | Imposta il valore del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | Restituisce il valore per la _key_. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Inizializza una nuova istanza della classe [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Aggiunge il valore alla chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| valore | string | Il valore a cui aggiungere. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Aggiunge il valore alla chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| valore | System.Object | Il valore a cui aggiungere. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Determina se questa collezione contiene la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave da verificare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | **True** se il  contiene la chiave specificata; altrimenti, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Restituisce l'oggetto con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave che identifica il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Object | Restituisce l'oggetto con la chiave specificata. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Converte il valore XMP nella rappresentazione XML.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore XMP convertito nella rappresentazione XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Rimuove il valore con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore rimosso. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce true se il valore con la chiave specificata è stato rimosso. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

Imposta l'istituzione dell'apparecchiatura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| equipment_institution | string | L'istituzione dell'apparecchiatura. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Imposta il produttore dell'apparecchiatura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| equipment_manufacturer | string | Il produttore dell'apparecchiatura. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

Imposta la data di nascita del paziente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| patient_birth_date | string | La data di nascita del paziente. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

Imposta l'ID del paziente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| patient_id | string | L'ID del paziente. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

Imposta la modalità colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| patient_name | string | Il nome del paziente. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

Imposta il sesso del paziente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| patient_sex | string | Il sesso del paziente. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Restituisce o imposta l'oggetto con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave che identifica il valore. |
| valore | System.Object | L'oggetto con la chiave specificata. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

Imposta la data e ora della serie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| series_date_time | string | La data e ora della serie. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

Imposta la descrizione della serie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| series_description | string | La descrizione della serie. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

Imposta la modalità della serie di documenti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| series_modality | string | La modalità della serie. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

Imposta il numero della serie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| series_number | string | Il numero della serie. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

Imposta la data e ora dello studio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| study_date_time | string | Il studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

Imposta la descrizione dello studio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| study_description | string | La descrizione dello studio. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

Imposta l'ID dello studio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| study_id | string | L'ID dello studio. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

Imposta il medico dello studio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| study_physician | string | Il medico dello studio. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Il valore a cui aggiungere. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Il valore da impostare. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

Restituisce il valore per la _key_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave dell'elemento XMP. |
| valore | System.Object | Il valore XMP. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | **True**, se il  contiene la _key_; altrimenti, **False**. |


