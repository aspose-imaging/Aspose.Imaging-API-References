---
title: "Класс PdfPackage"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Создаёт новый экземпляр класса [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/). |
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
| [set_keywords(keywords)](#set_keywords_keywords_7) | Устанавливает ключевые слова. |
| [set_pdf_version(version)](#set_pdf_version_version_8) | Устанавливает версию PDF. |
| [set_producer(producer)](#set_producer_producer_9) | Устанавливает имя инструмента, создавшего PDF. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Получает или задаёт объект с указанным ключом. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | Устанавливает trapped. |
| [set_value(key, value)](#set_value_key_value_12) | Устанавливает значение. |
| [set_value(key, value)](#set_value_key_value_13) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | Устанавливает значение типа XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | Получает значение по _key_. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Создаёт новый экземпляр класса [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/).

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

Устанавливает ключевые слова.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ключевые слова | string | Ключевые слова. |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

Устанавливает версию PDF.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| version | string | Версия PDF, например: 1.0, 1.3 и т.д. |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

Устанавливает имя инструмента, создавшего PDF.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| производитель | string | Имя производителя. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

Получает или задаёт объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |
| значение | System.Object | Объект с указанным ключом. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

Устанавливает trapped.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| is_trapped | bool | если установлено <c>true</c>, документ был захвачен. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Значение для добавления. |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Значение для добавления. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с установленным значением. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Значение для установки. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


