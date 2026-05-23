---
title: "DicomPackage Clase"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Inicializa una nueva instancia de la clase [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| count | int | r | Obtiene el recuento de claves XMP. |
| namespace_uri | string | r | Obtiene el URI del espacio de nombres. |
| prefix | string | r | Obtiene el prefijo. |
| xml_namespace | string | r | Obtiene el espacio de nombres XML. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Agrega el valor a la clave especificada. |
| [add_value(key, value)](#add_value_key_value_2) | Agrega el valor a la clave especificada. |
| clear() | Borra esta instancia. |
| [contains_key(key)](#contains_key_key_3) | Determina si esta colección contiene la clave especificada. |
| [get_prop_value(key)](#get_prop_value_key_4) | Obtiene el objeto con la clave especificada. |
| [get_xml_value()](#get_xml_value__5) | Convierte el valor XMP a la representación XML. |
| [remove(key)](#remove_key_6) | Elimina el valor con la clave especificada. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | Establece la institución del equipo. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | Establece el fabricante del equipo. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | Establece la fecha de nacimiento del paciente. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | Establece el ID del paciente. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | Establece el modo de color. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | Establece el sexo del paciente. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Obtiene o establece el objeto con la clave especificada. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | Establece la fecha y hora de la serie. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | Establece la descripción de la serie. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | Establece la modalidad de la serie del documento. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | Establece el número de la serie. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | Establece la fecha y hora del estudio. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | Establece la descripción del estudio. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | Establece el ID del estudio. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | Establece el médico del estudio. |
| [set_value(key, value)](#set_value_key_value_22) | Establece el valor. |
| [set_value(key, value)](#set_value_key_value_23) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | Establece el valor del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | Obtiene el valor por la _clave_. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Inicializa una nueva instancia de la clase [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Agrega el valor a la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | string | El valor al que agregar. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Agrega el valor a la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | System.Object | El valor al que agregar. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Determina si esta colección contiene la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave a comprobar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | **True** si el contiene la clave especificada; de lo contrario, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Obtiene el objeto con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave que identifica el valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object | Devuelve el objeto con la clave especificada. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Convierte el valor XMP a la representación XML.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a la representación XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Elimina el valor con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor eliminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve verdadero si el valor con la clave especificada fue eliminado. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

Establece la institución del equipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| equipment_institution | string | La institución del equipo. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Establece el fabricante del equipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| equipment_manufacturer | string | El fabricante del equipo. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

Establece la fecha de nacimiento del paciente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| patient_birth_date | string | La fecha de nacimiento del paciente. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

Establece el ID del paciente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| patient_id | string | El ID del paciente. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

Establece el modo de color.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| patient_name | string | El nombre del paciente. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

Establece el sexo del paciente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| patient_sex | string | El sexo del paciente. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Obtiene o establece el objeto con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave que identifica el valor. |
| valor | System.Object | El objeto con la clave especificada. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

Establece la fecha y hora de la serie.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| series_date_time | string | La fecha y hora de la serie. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

Establece la descripción de la serie.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| series_description | string | La descripción de la serie. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

Establece la modalidad de la serie del documento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| series_modality | string | La modalidad de la serie. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

Establece el número de la serie.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| series_number | string | El número de la serie. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

Establece la fecha y hora del estudio.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| study_date_time | string | El studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

Establece la descripción del estudio.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| study_description | string | La descripción del estudio. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

Establece el ID del estudio.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| study_id | string | El ID del estudio. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

Establece el médico del estudio.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| study_physician | string | El médico del estudio. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | El valor al que agregar. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | El valor al que establecer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

Obtiene el valor por la _clave_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave del elemento XMP. |
| valor | System.Object | El valor XMP. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | **True**, si el contiene la _key_; de lo contrario, **False**. |


