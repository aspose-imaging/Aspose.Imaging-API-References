---
title: "DicomPackage Classe"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Initialise une nouvelle instance de la classe [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Obtient le nombre de clés XMP. |
| namespace_uri | string | r | Obtient l'URI de l'espace de noms. |
| prefix | string | r | Obtient le préfixe. |
| xml_namespace | string | r | Obtient l'espace de noms XML. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Ajoute la valeur à la clé spécifiée. |
| [add_value(key, value)](#add_value_key_value_2) | Ajoute la valeur à la clé spécifiée. |
| clear() | Efface cette instance. |
| [contains_key(key)](#contains_key_key_3) | Détermine si cette collection possède la clé spécifiée. |
| [get_prop_value(key)](#get_prop_value_key_4) | Obtient l'objet avec la clé spécifiée. |
| [get_xml_value()](#get_xml_value__5) | Convertit la valeur XMP en représentation XML. |
| [remove(key)](#remove_key_6) | Supprime la valeur avec la clé spécifiée. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | Définit l'institution de l'équipement. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | Définit le fabricant de l'équipement. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | Définit la date de naissance du patient. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | Définit l'ID du patient. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | Définit le mode couleur. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | Définit le sexe du patient. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Obtient ou définit l'objet avec la clé spécifiée. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | Définit la date et l'heure de la série. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | Définit la description de la série. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | Définit la modalité de la série de documents. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | Définit le numéro de la série. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | Définit la date et l'heure de l'étude. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | Définit la description de l'étude. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | Définit l'ID de l'étude. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | Définit le médecin de l'étude. |
| [set_value(key, value)](#set_value_key_value_22) | Définit la valeur. |
| [set_value(key, value)](#set_value_key_value_23) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | Définit la valeur du type XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | Obtient la valeur par la _key_. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Initialise une nouvelle instance de la classe [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Ajoute la valeur à la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | string | La valeur à ajouter à. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Ajoute la valeur à la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | System.Object | La valeur à ajouter à. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Détermine si cette collection possède la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé à vérifier. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** si le  contient la clé spécifiée ; sinon, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Obtient l'objet avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé qui identifie la valeur. |

**Returns**

| Type | Description |
| :- | :- |
| System.Object | Renvoie l'objet avec la clé spécifiée. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Convertit la valeur XMP en représentation XML.

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie la valeur XMP convertie en représentation XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Supprime la valeur avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé identifiée avec la valeur supprimée. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie true si la valeur avec la clé spécifiée a été supprimée. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

Définit l'institution de l'équipement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| equipment_institution | string | L'institution de l'équipement. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Définit le fabricant de l'équipement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| equipment_manufacturer | string | Le fabricant de l'équipement. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

Définit la date de naissance du patient.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| patient_birth_date | string | La date de naissance du patient. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

Définit l'ID du patient.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| patient_id | string | L'ID du patient. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

Définit le mode couleur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| patient_name | string | Le nom du patient. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

Définit le sexe du patient.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| patient_sex | string | Le sexe du patient. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Obtient ou définit l'objet avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé qui identifie la valeur. |
| value | System.Object | L'objet avec la clé spécifiée. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

Définit la date et l'heure de la série.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| series_date_time | string | La date et l'heure de la série. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

Définit la description de la série.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| series_description | string | La description de la série. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

Définit la modalité de la série de documents.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| series_modality | string | La modalité de la série. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

Définit le numéro de la série.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| series_number | string | Le numéro de la série. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

Définit la date et l'heure de l'étude.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| study_date_time | string | Le studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

Définit la description de l'étude.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| study_description | string | La description de l'étude. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

Définit l'ID de l'étude.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| study_id | string | L'ID de l'étude. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

Définit le médecin de l'étude.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| study_physician | string | Le médecin de l'étude. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | La valeur à ajouter à. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | La valeur à définir à. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

Obtient la valeur par la _key_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé de l'élément XMP. |
| value | System.Object | La valeur XMP. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True**, si le  contient la _key_; sinon, **False**. |


