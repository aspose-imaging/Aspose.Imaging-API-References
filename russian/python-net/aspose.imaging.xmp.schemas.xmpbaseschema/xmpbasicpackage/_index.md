---
title: "XmpBasicPackage Класс"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Инициализирует новый экземпляр [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) класса. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Инициализирует новый экземпляр [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) класса. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Максимальное значение рейтинга. |
| RATING_MIN [static] | int | r | Минимальное значение рейтинга. |
| RATING_REJECTED [static] | int | r | Отвергнутое значение рейтинга. |
| count | int | r | Получает количество ключей XMP. |
| namespace_uri | string | r | Получает URI пространства имён. |
| prefix | string | r | Получает префикс. |
| xml_namespace | string | r | Получает XML‑пространство имён. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Добавляет строковое свойство. |
| [add_value(key, value)](#add_value_key_value_2) | Добавляет строковое свойство. |
| clear() | Очищает этот экземпляр. |
| [contains_key(key)](#contains_key_key_3) | Определяет, содержит ли эта коллекция указанный ключ. |
| [get_prop_value(key)](#get_prop_value_key_4) | Получает объект с указанным ключом. |
| [get_xml_value()](#get_xml_value__5) | Преобразует значение XMP в XML‑представление. |
| [remove(key)](#remove_key_6) | Удаляет значение с указанным ключом. |
| [set_created_date(created_date)](#set_created_date_created_date_7) | Добавляет дату создания ресурса. |
| [set_created_date(created_date)](#set_created_date_created_date_8) | Добавляет дату создания ресурса. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | Добавляет дату создания ресурса. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | Устанавливает инструмент создателя. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | Устанавливает идентификатор. |
| [set_label(label)](#set_label_label_12) | Устанавливает метку. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Добавляет дату последнего изменения метаданных. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | Добавляет дату последнего изменения метаданных. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | Добавляет дату последнего изменения метаданных. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Добавляет дату последнего изменения ресурса. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | Добавляет дату последнего изменения ресурса. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | Добавляет дату последнего изменения ресурса. |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | Получает или задаёт объект с указанным ключом. |
| [set_rating(choise)](#set_rating_choise_20) | Устанавливает рейтинг. |
| [set_value(key, value)](#set_value_key_value_21) | Устанавливает значение. |
| [set_value(key, value)](#set_value_key_value_22) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | Устанавливает значение типа XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_24) | Получает значение по _key_. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Инициализирует новый экземпляр [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) класса.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Инициализирует новый экземпляр [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| prefix | string | Префикс. |
| namespace_uri | string | URI пространства имен. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Добавляет строковое свойство.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| значение | string | Строковое значение. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Добавляет строковое свойство.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| значение | System.Object | Строковое значение. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Добавляет дату создания ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| created_date | System.DateTime | Дата создания. |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

Добавляет дату создания ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| created_date | string | Дата создания. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

Добавляет дату создания ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| created_date | string | Дата создания. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

Устанавливает инструмент создателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| creator_tool | string | Название инструмента. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

Устанавливает идентификатор.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| идентификатор | string[] | Идентификатор. |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

Устанавливает метку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| метка | string | Метка. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Добавляет дату последнего изменения метаданных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata_date | System.DateTime | Дата метаданных. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

Добавляет дату последнего изменения метаданных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata_date | string | Дата метаданных. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

Добавляет дату последнего изменения метаданных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata_date | string | Дата метаданных. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Добавляет дату последнего изменения ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| modified_date | System.DateTime | Дата последнего изменения. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

Добавляет дату последнего изменения ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| modified_date | string | Дата последнего изменения. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

Добавляет дату последнего изменения ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| modified_date | string | Дата последнего изменения. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

Получает или задаёт объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |
| значение | System.Object | Объект с указанным ключом. |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

Устанавливает рейтинг.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| выбор | int | От -1 до 5 |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Значение для добавления. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Значение для добавления. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с установленным значением. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Значение для установки. |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


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


