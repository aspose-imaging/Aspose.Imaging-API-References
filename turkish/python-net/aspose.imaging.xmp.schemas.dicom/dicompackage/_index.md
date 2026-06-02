---
title: "DicomPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | Yeni bir [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| count | int | r | XMP anahtar sayısını alır. |
| namespace_uri | string | r | Namespace URI'sini alır. |
| prefix | string | r | Öneki alır. |
| xml_namespace | string | r | XML ad alanını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Belirtilen anahtara değeri ekler. |
| [add_value(key, value)](#add_value_key_value_2) | Belirtilen anahtara değeri ekler. |
| clear() | Bu örneği temizler. |
| [contains_key(key)](#contains_key_key_3) | Bu koleksiyonun belirtilen anahtarı içerip içermediğini belirler. |
| [get_prop_value(key)](#get_prop_value_key_4) | Belirtilen anahtara sahip nesneyi alır. |
| [get_xml_value()](#get_xml_value__5) | XMP değerini XML temsiline dönüştürür. |
| [remove(key)](#remove_key_6) | Belirtilen anahtara sahip değeri kaldırır. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | Ekipman kurumunu ayarlar. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | Ekipman üreticisini ayarlar. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | Hastanın doğum tarihini ayarlar. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | Hastanın kimliğini ayarlar. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | Renk modunu ayarlar. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | Hastanın cinsiyetini ayarlar. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | Seri tarih ve saatini ayarlar. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | Seri açıklamasını ayarlar. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | Belge serisi modunu ayarlar. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | Seri numarasını ayarlar. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | Çalışma tarih ve saatini ayarlar. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | Çalışma açıklamasını ayarlar. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | Çalışma kimliğini ayarlar. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | Çalışma hekimini ayarlar. |
| [set_value(key, value)](#set_value_key_value_22) | Değeri ayarlar. |
| [set_value(key, value)](#set_value_key_value_23) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | XMP tip değerini ayarlar. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | Değeri _key_ ile alır. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

Yeni bir [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) sınıfının bir örneğini başlatır.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Belirtilen anahtara değeri ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | string | Eklenecek değer. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Belirtilen anahtara değeri ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | System.Object | Eklenecek değer. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Bu koleksiyonun belirtilen anahtarı içerip içermediğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Kontrol edilecek anahtar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | **True** eğer belirtilen anahtarı içeriyorsa; aksi takdirde, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Belirtilen anahtara sahip nesneyi alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Değeri tanımlayan anahtar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object | Belirtilen anahtara sahip nesneyi döndürür. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

XMP değerini XML temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP değerini XML temsiline dönüştürülmüş olarak döndürür. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Belirtilen anahtara sahip değeri kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Kaldırılan değerle tanımlanan anahtarın dize temsili. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen anahtara sahip değer kaldırıldıysa true döndürür. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

Ekipman kurumunu ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| equipment_institution | string | Ekipman kurumu. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

Ekipman üreticisini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| equipment_manufacturer | string | Ekipman üreticisi. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

Hastanın doğum tarihini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| patient_birth_date | string | Hastanın doğum tarihi. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

Hastanın kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| patient_id | string | Hastanın kimliği. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

Renk modunu ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| patient_name | string | Hastanın adı. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

Hastanın cinsiyetini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| patient_sex | string | Hastanın cinsiyeti. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Belirtilen anahtara sahip nesneyi alır veya ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Değeri tanımlayan anahtar. |
| değer | System.Object | Belirtilen anahtara sahip nesne. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

Seri tarih ve saatini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| series_date_time | string | Seri tarih ve saat. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

Seri açıklamasını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| series_description | string | Seri açıklaması. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

Belge serisi modunu ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| series_modality | string | Seri modalitesi. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

Seri numarasını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| series_number | string | Seri numarası. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

Çalışma tarih ve saatini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| study_date_time | string | Bu studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

Çalışma açıklamasını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| study_description | string | Çalışma açıklaması. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

Çalışma kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| study_id | string | Bu study ID. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

Çalışma hekimini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| study_physician | string | Çalışma hekimi. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Eklenecek değer. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Eklenecek değer. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

XMP tip değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Ayarlanacak değer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

Değeri _key_ ile alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | XMP öğe anahtarı. |
| değer | System.Object | XMP değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | **True**, eğer  _key_ içeriyorsa; aksi takdirde, **False**. |


