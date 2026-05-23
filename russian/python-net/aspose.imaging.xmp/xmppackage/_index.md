---
title: "XmpPackage Класс"
type: docs
weight: 460
url: /ru/python-net/aspose.imaging.xmp/xmppackage/
---

**Summary:** Represents base abstraction for XMP package.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackage

**Inheritance:** IXmlValue

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
| [set_prop_value(key, value)](#set_prop_value_key_value_7) | Получает или задаёт объект с указанным ключом. |
| [set_value(key, value)](#set_value_key_value_8) | Устанавливает значение. |
| [set_value(key, value)](#set_value_key_value_9) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Устанавливает значение типа XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_11) | Получает значение по _key_. |


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


### Method: set_prop_value(key, value) {#set_prop_value_key_value_7}


```
 set_prop_value(key, value) 
```

Получает или задаёт объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |
| значение | System.Object | Объект с указанным ключом. |

### Method: set_value(key, value) {#set_value_key_value_8}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Значение для добавления. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Значение для добавления. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с установленным значением. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Значение для установки. |

### Method: try_get_value(key, value) {#try_get_value_key_value_11}


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


