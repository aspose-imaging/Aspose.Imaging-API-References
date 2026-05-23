---
title: "Класс XmpMediaManagementPackage"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpmm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Инициализирует новый экземпляр класса [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/). |
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
| [add_value(key, value)](#add_value_key_value_1) | Добавляет строковое свойство. |
| [add_value(key, value)](#add_value_key_value_2) | Добавляет строковое свойство. |
| clear() | Очищает этот экземпляр. |
| [contains_key(key)](#contains_key_key_3) | Определяет, содержит ли эта коллекция указанный ключ. |
| [get_prop_value(key)](#get_prop_value_key_4) | Получает объект с указанным ключом. |
| [get_xml_value()](#get_xml_value__5) | Преобразует значение XMP в XML‑представление. |
| [remove(key)](#remove_key_6) | Удаляет значение с указанным ключом. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_7) | Устанавливает значение derived from. |
| [set_document_id(guid)](#set_document_id_guid_8) | Устанавливает идентификатор документа. |
| [set_document_id(guid)](#set_document_id_guid_9) | Устанавливает идентификатор документа. |
| [set_document_id_as_guid(guid)](#set_document_id_as_guid_guid_10) | Устанавливает идентификатор документа. |
| [set_instance_id(guid)](#set_instance_id_guid_11) | Устанавливает идентификатор экземпляра. |
| [set_instance_id(guid)](#set_instance_id_guid_12) | Устанавливает идентификатор экземпляра. |
| [set_instance_id_as_guid(guid)](#set_instance_id_as_guid_guid_13) | Устанавливает идентификатор экземпляра. |
| [set_original_document_id(guid)](#set_original_document_id_guid_14) | Устанавливает идентификатор оригинального документа. |
| [set_original_document_id(guid)](#set_original_document_id_guid_15) | Устанавливает идентификатор оригинального документа. |
| [set_original_document_id_as_guid(guid)](#set_original_document_id_as_guid_guid_16) | Устанавливает идентификатор оригинального документа. |
| [set_prop_value(key, value)](#set_prop_value_key_value_17) | Получает или задаёт объект с указанным ключом. |
| [set_value(key, value)](#set_value_key_value_18) | Устанавливает значение. |
| [set_value(key, value)](#set_value_key_value_19) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_20) | Устанавливает значение типа XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_21) | Получает значение по _key_. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Инициализирует новый экземпляр класса [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/).

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_7}


```
 set_derived_from(resource_ref) 
```

Устанавливает значение derived from.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| resource_ref | [ResourceRef](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceref/resourceref/) | Ссылка на ресурс. |

### Method: set_document_id(guid) {#set_document_id_guid_8}


```
 set_document_id(guid) 
```

Устанавливает идентификатор документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | System.Guid | Уникальный идентификатор. |

### Method: set_document_id(guid) {#set_document_id_guid_9}


```
 set_document_id(guid) 
```

Устанавливает идентификатор документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | string | Уникальный идентификатор. |

### Method: set_document_id_as_guid(guid) {#set_document_id_as_guid_guid_10}


```
 set_document_id_as_guid(guid) 
```

Устанавливает идентификатор документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | System.Guid | Уникальный идентификатор. |

### Method: set_instance_id(guid) {#set_instance_id_guid_11}


```
 set_instance_id(guid) 
```

Устанавливает идентификатор экземпляра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | System.Guid | Уникальный идентификатор. |

### Method: set_instance_id(guid) {#set_instance_id_guid_12}


```
 set_instance_id(guid) 
```

Устанавливает идентификатор экземпляра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | string | Уникальный идентификатор. |

### Method: set_instance_id_as_guid(guid) {#set_instance_id_as_guid_guid_13}


```
 set_instance_id_as_guid(guid) 
```

Устанавливает идентификатор экземпляра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | System.Guid | Уникальный идентификатор. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_14}


```
 set_original_document_id(guid) 
```

Устанавливает идентификатор оригинального документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | System.Guid | Уникальный идентификатор. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_15}


```
 set_original_document_id(guid) 
```

Устанавливает идентификатор оригинального документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | string | Уникальный идентификатор. |

### Method: set_original_document_id_as_guid(guid) {#set_original_document_id_as_guid_guid_16}


```
 set_original_document_id_as_guid(guid) 
```

Устанавливает идентификатор оригинального документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | System.Guid | Уникальный идентификатор. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_17}


```
 set_prop_value(key, value) 
```

Получает или задаёт объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |
| значение | System.Object | Объект с указанным ключом. |

### Method: set_value(key, value) {#set_value_key_value_18}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Значение для добавления. |

### Method: set_value(key, value) {#set_value_key_value_19}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Значение для добавления. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_20}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с установленным значением. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Значение для установки. |

### Method: try_get_value(key, value) {#try_get_value_key_value_21}


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


