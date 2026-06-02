---
title: "DicomPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | 初始化 [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| count | int | r | 获取 XMP 键的计数。 |
| namespace_uri | string | r | 获取命名空间 URI。 |
| prefix | string | r | 获取前缀。 |
| xml_namespace | string | r | 获取 XML 命名空间。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 将值添加到指定的键。 |
| [add_value(key, value)](#add_value_key_value_2) | 将值添加到指定的键。 |
| clear() | 清除此实例。 |
| [contains_key(key)](#contains_key_key_3) | 确定此集合是否指定了键。 |
| [get_prop_value(key)](#get_prop_value_key_4) | 获取具有指定键的对象。 |
| [get_xml_value()](#get_xml_value__5) | 将 XMP 值转换为 XML 表示。 |
| [remove(key)](#remove_key_6) | 移除具有指定键的值。 |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | 设置设备机构。 |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | 设置设备制造商。 |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | 设置患者的出生日期。 |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | 设置患者的 ID。 |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | 设置颜色模式。 |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | 设置患者的性别。 |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | 获取或设置具有指定键的对象。 |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | 设置序列日期时间。 |
| [set_series_description(series_description)](#set_series_description_series_description_15) | 设置序列描述。 |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | 设置文档序列模式。 |
| [set_series_number(series_number)](#set_series_number_series_number_17) | 设置序列号。 |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | 设置研究日期时间。 |
| [set_study_description(study_description)](#set_study_description_study_description_19) | 设置研究描述。 |
| [set_study_id(study_id)](#set_study_id_study_id_20) | 设置研究 ID。 |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | 设置研究医师。 |
| [set_value(key, value)](#set_value_key_value_22) | 设置值。 |
| [set_value(key, value)](#set_value_key_value_23) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | 设置 XMP 类型值。 |
| [try_get_value(key, value)](#try_get_value_key_value_25) | 获取通过 _key_ 的值。 |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

初始化 [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) 类的新实例。

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

将值添加到指定的键。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | string | 要添加到的值。 |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

将值添加到指定的键。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | System.Object | 要添加到的值。 |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

确定此集合是否指定了键。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 要检查的键。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** 如果包含指定键；否则，**False**。 |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

获取具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Object | 返回具有指定键的对象。 |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回转换为 XML 表示形式的 XMP 值。 |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

移除具有指定键的值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已删除值对应键的字符串表示。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果已删除具有指定键的值，则返回 true。 |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

设置设备机构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| equipment_institution | string | 设备机构。 |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

设置设备制造商。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| equipment_manufacturer | string | 设备制造商。 |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

设置患者的出生日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| patient_birth_date | string | 患者的出生日期。 |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

设置患者的 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| patient_id | string | 患者的 ID。 |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

设置颜色模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| patient_name | string | 患者的姓名。 |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

设置患者的性别。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| patient_sex | string | 患者的性别。 |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

获取或设置具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |
| value | System.Object | 具有指定键的对象。 |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

设置序列日期时间。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| series_date_time | string | 系列的日期时间。 |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

设置序列描述。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| series_description | string | 系列的描述。 |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

设置文档序列模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| series_modality | string | 系列的模态。 |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

设置序列号。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| series_number | string | 系列的编号。 |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

设置研究日期时间。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| study_date_time | string | 该 studyDateTime。 |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

设置研究描述。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| study_description | string | 研究的描述。 |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

设置研究 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| study_id | string | 该研究 ID。 |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

设置研究医师。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| study_physician | string | 研究的医师。 |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | 要添加到的值。 |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | 要添加到的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已设置值对应键的字符串表示。 |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | 要设置的值。 |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

获取通过 _key_ 的值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | XMP 元素键。 |
| value | System.Object | XMP 值。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True**，如果该  包含 _key_；否则为 **False**。 |


