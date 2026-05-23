---
title: "Класс DicomPackage"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Инициализирует новый экземпляр класса [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Получает количество ключей XMP. |
| namespace_uri | string | r | Получает URI пространства имён. |
| prefix | string | r | Получает префикс. |
| xml_namespace | string | r | Получает XML‑пространство имён. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Добавляет значение к указанному ключу. |
| [add_value(key, value)](#add_value_key_value_2) | Добавляет значение к указанному ключу. |
| clear() | Очищает этот экземпляр. |
| [contains_key(key)](#contains_key_key_3) | Определяет, содержит ли эта коллекция указанный ключ. |
| [get_prop_value(key)](#get_prop_value_key_4) | Получает объект с указанным ключом. |
| [get_xml_value()](#get_xml_value__5) | Преобразует значение XMP в XML‑представление. |
| [remove(key)](#remove_key_6) | Удаляет значение с указанным ключом. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | Устанавливает учреждение оборудования. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | Устанавливает производителя оборудования. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | Устанавливает дату рождения пациента. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | Устанавливает идентификатор пациента. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | Устанавливает режим цвета. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | Устанавливает пол пациента. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Получает или задаёт объект с указанным ключом. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | Устанавливает дату и время серии. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | Устанавливает описание серии. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | Устанавливает модальность серии документа. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | Устанавливает номер серии. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | Устанавливает дату и время исследования. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | Устанавливает описание исследования. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | Устанавливает идентификатор исследования. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | Устанавливает врача исследования. |
| [set_value(key, value)](#set_value_key_value_22) | Устанавливает значение. |
| [set_value(key, value)](#set_value_key_value_23) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | Устанавливает значение типа XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | Получает значение по _key_. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Инициализирует новый экземпляр класса [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Добавляет значение к указанному ключу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| значение | string | Значение для добавления. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Добавляет значение к указанному ключу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| значение | System.Object | Значение для добавления. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Определяет, содержит ли эта коллекция указанный ключ.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | **True** если объект содержит указанный ключ; иначе, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Получает объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object | Возвращает объект с указанным ключом. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Преобразует значение XMP в XML‑представление.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает значение XMP, преобразованное в представление XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Удаляет значение с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с удалённым значением. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Возвращает true, если значение с указанным ключом было удалено. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

Устанавливает учреждение оборудования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| equipment_institution | string | Учреждение оборудования. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Устанавливает производителя оборудования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| equipment_manufacturer | string | Производитель оборудования. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

Устанавливает дату рождения пациента.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| patient_birth_date | string | Дата рождения пациента. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

Устанавливает идентификатор пациента.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| patient_id | string | Идентификатор пациента. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

Устанавливает режим цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| patient_name | string | Имя пациента. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

Устанавливает пол пациента.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| patient_sex | string | Пол пациента. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Получает или задаёт объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |
| значение | System.Object | Объект с указанным ключом. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

Устанавливает дату и время серии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| series_date_time | string | Дата и время серии. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

Устанавливает описание серии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| series_description | string | Описание серии. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

Устанавливает модальность серии документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| series_modality | string | Модальность серии. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

Устанавливает номер серии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| series_number | string | Номер серии. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

Устанавливает дату и время исследования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| study_date_time | string | Свойство studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

Устанавливает описание исследования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| study_description | string | Описание исследования. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

Устанавливает идентификатор исследования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| study_id | string | Идентификатор исследования. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

Устанавливает врача исследования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| study_physician | string | Врач исследования. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Значение для добавления. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Значение для добавления. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с установленным значением. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Значение для установки. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

Получает значение по _key_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ элемента XMP. |
| значение | System.Object | Значение XMP. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | **True**, если содержит _key_; иначе **False**. |


