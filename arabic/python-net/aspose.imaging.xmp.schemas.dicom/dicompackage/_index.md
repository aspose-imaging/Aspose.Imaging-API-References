---
title: "فئة DicomPackage"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/
---

**Summary:** The Dicom Xmp package.

**Module:** [aspose.imaging.xmp.schemas.dicom](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/)

**Full Name:** aspose.imaging.xmp.schemas.dicom.DicomPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [DicomPackage()](#DicomPackage__1) | يُنشئ مثيلًا جديدًا من [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) الفئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| count | int | r | يحصل على عدد مفاتيح XMP. |
| namespace_uri | string | r | يسترجع مساحة الاسم URI. |
| prefix | string | r | يسترجع البادئة. |
| xml_namespace | string | r | يسترجع مساحة الاسم XML. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | يضيف القيمة إلى المفتاح المحدد. |
| [add_value(key, value)](#add_value_key_value_2) | يضيف القيمة إلى المفتاح المحدد. |
| clear() | يمسح هذا الكائن. |
| [contains_key(key)](#contains_key_key_3) | يحدد ما إذا كانت هذه المجموعة تحتوي على المفتاح المحدد. |
| [get_prop_value(key)](#get_prop_value_key_4) | يسترجع الكائن بالمفتاح المحدد. |
| [get_xml_value()](#get_xml_value__5) | يحوّل قيمة XMP إلى تمثيل XML. |
| [remove(key)](#remove_key_6) | إزالة القيمة بالمفتاح المحدد. |
| [set_equipment_institution(equipment_institution)](#set_equipment_institution_equipment_institution_7) | يضبط مؤسسة الجهاز. |
| [set_equipment_manufacturer(equipment_manufacturer)](#set_equipment_manufacturer_equipment_manufacturer_8) | يضبط مصنع الجهاز. |
| [set_patient_birth_date(patient_birth_date)](#set_patient_birth_date_patient_birth_date_9) | يضبط تاريخ ميلاد المريض. |
| [set_patient_id(patient_id)](#set_patient_id_patient_id_10) | يضبط معرف المريض. |
| [set_patient_name(patient_name)](#set_patient_name_patient_name_11) | يضبط وضع اللون. |
| [set_patient_sex(patient_sex)](#set_patient_sex_patient_sex_12) | يضبط جنس المريض. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | يسترجع أو يعيّن الكائن بالمفتاح المحدد. |
| [set_series_date_time(series_date_time)](#set_series_date_time_series_date_time_14) | يضبط تاريخ ووقت السلسلة. |
| [set_series_description(series_description)](#set_series_description_series_description_15) | يضبط وصف السلسلة. |
| [set_series_modality(series_modality)](#set_series_modality_series_modality_16) | يضبط نمط سلسلة المستند. |
| [set_series_number(series_number)](#set_series_number_series_number_17) | يضبط رقم السلسلة. |
| [set_study_date_time(study_date_time)](#set_study_date_time_study_date_time_18) | يضبط تاريخ ووقت الدراسة. |
| [set_study_description(study_description)](#set_study_description_study_description_19) | يضبط وصف الدراسة. |
| [set_study_id(study_id)](#set_study_id_study_id_20) | يضبط معرف الدراسة. |
| [set_study_physician(study_physician)](#set_study_physician_study_physician_21) | يضبط طبيب الدراسة. |
| [set_value(key, value)](#set_value_key_value_22) | يعيّن القيمة. |
| [set_value(key, value)](#set_value_key_value_23) | يعيّن القيمة. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | يعيّن قيمة نوع XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_25) | يسترجع القيمة حسب _key_. |


### Constructor: DicomPackage() {#DicomPackage__1}


```
 DicomPackage() 
```

يُنشئ مثيلًا جديدًا من [DicomPackage](/imaging/python-net/aspose.imaging.xmp.schemas.dicom/dicompackage/) الفئة.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

يضيف القيمة إلى المفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | string | القيمة للإضافة إلى. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

يضيف القيمة إلى المفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | System.Object | القيمة للإضافة إلى. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

يحدد ما إذا كانت هذه المجموعة تحتوي على المفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي سيتم فحصه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | **True** إذا كان   يحتوي على المفتاح المحدد؛ وإلا، **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

يسترجع الكائن بالمفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي يحدد القيمة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object | يعيد الكائن بالمفتاح المحدد. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

يحوّل قيمة XMP إلى تمثيل XML.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يعيد قيمة XMP محوّلة إلى تمثيل XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

إزالة القيمة بالمفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | التمثيل النصي للمفتاح الذي تم تحديده بالقيمة المحذوفة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | يعيد true إذا تمت إزالة القيمة ذات المفتاح المحدد. |


### Method: set_equipment_institution(equipment_institution) {#set_equipment_institution_equipment_institution_7}


```
 set_equipment_institution(equipment_institution) 
```

يضبط مؤسسة الجهاز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| equipment_institution | string | مؤسسة الجهاز. |

### Method: set_equipment_manufacturer(equipment_manufacturer) {#set_equipment_manufacturer_equipment_manufacturer_8}


```
 set_equipment_manufacturer(equipment_manufacturer) 
```

يضبط مصنع الجهاز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| equipment_manufacturer | string | مصنع الجهاز. |

### Method: set_patient_birth_date(patient_birth_date) {#set_patient_birth_date_patient_birth_date_9}


```
 set_patient_birth_date(patient_birth_date) 
```

يضبط تاريخ ميلاد المريض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| patient_birth_date | string | تاريخ ميلاد المريض. |

### Method: set_patient_id(patient_id) {#set_patient_id_patient_id_10}


```
 set_patient_id(patient_id) 
```

يضبط معرف المريض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| patient_id | string | معرف المريض. |

### Method: set_patient_name(patient_name) {#set_patient_name_patient_name_11}


```
 set_patient_name(patient_name) 
```

يضبط وضع اللون.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| patient_name | string | اسم المريض. |

### Method: set_patient_sex(patient_sex) {#set_patient_sex_patient_sex_12}


```
 set_patient_sex(patient_sex) 
```

يضبط جنس المريض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| patient_sex | string | جنس المريض. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

يسترجع أو يعيّن الكائن بالمفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي يحدد القيمة. |
| القيمة | System.Object | الكائن بالمفتاح المحدد. |

### Method: set_series_date_time(series_date_time) {#set_series_date_time_series_date_time_14}


```
 set_series_date_time(series_date_time) 
```

يضبط تاريخ ووقت السلسلة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| series_date_time | string | تاريخ ووقت السلسلة. |

### Method: set_series_description(series_description) {#set_series_description_series_description_15}


```
 set_series_description(series_description) 
```

يضبط وصف السلسلة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| series_description | string | وصف السلسلة. |

### Method: set_series_modality(series_modality) {#set_series_modality_series_modality_16}


```
 set_series_modality(series_modality) 
```

يضبط نمط سلسلة المستند.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| series_modality | string | طريقة السلسلة. |

### Method: set_series_number(series_number) {#set_series_number_series_number_17}


```
 set_series_number(series_number) 
```

يضبط رقم السلسلة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| series_number | string | رقم السلسلة. |

### Method: set_study_date_time(study_date_time) {#set_study_date_time_study_date_time_18}


```
 set_study_date_time(study_date_time) 
```

يضبط تاريخ ووقت الدراسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| study_date_time | string | الـ studyDateTime. |

### Method: set_study_description(study_description) {#set_study_description_study_description_19}


```
 set_study_description(study_description) 
```

يضبط وصف الدراسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| study_description | string | وصف الدراسة. |

### Method: set_study_id(study_id) {#set_study_id_study_id_20}


```
 set_study_id(study_id) 
```

يضبط معرف الدراسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| study_id | string | معرف الدراسة. |

### Method: set_study_physician(study_physician) {#set_study_physician_study_physician_21}


```
 set_study_physician(study_physician) 
```

يضبط طبيب الدراسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| study_physician | string | طبيب الدراسة. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

يعيّن القيمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | القيمة للإضافة إلى. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

يعيّن القيمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | القيمة للإضافة إلى. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

يعيّن قيمة نوع XMP.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | التمثيل النصي للمفتاح الذي تم تحديده بالقيمة المعينة. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | القيمة لتعيينها إلى. |

### Method: try_get_value(key, value) {#try_get_value_key_value_25}


```
 try_get_value(key, value) 
```

يسترجع القيمة حسب _key_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | مفتاح عنصر XMP. |
| القيمة | System.Object | قيمة XMP. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | **True**, إذا كان يحتوي على _key_; وإلا **False**. |


