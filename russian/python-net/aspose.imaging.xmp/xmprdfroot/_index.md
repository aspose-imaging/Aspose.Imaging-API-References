---
title: "XmpRdfRoot Класс"
type: docs
weight: 490
url: /ru/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Создает новый экземпляр [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) класса. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Добавляет атрибут. |
| clear_attributes() | Удаляет все атрибуты. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Получает атрибут. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Получает URI пространства имен по конкретному префиксу. Префикс может начинаться без xmlns. |
| [get_xml_value()](#get_xml_value__4) | Преобразует значение xmp в представление xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Добавляет URI пространства имен по префиксу. Префикс может начинаться без xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Создает новый экземпляр [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) класса.

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Добавляет атрибут.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| атрибут | string | Атрибут. |
| значение | string | Значение. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Получает атрибут.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| атрибут | string | Атрибут. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает атрибут для указанного имени атрибута. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Получает URI пространства имен по конкретному префиксу. Префикс может начинаться без xmlns.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| prefix | string | Префикс. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает URI схемы пакета. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Преобразует значение xmp в представление xml.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает значение XMP, преобразованное в строку XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Добавляет URI пространства имен по префиксу. Префикс может начинаться без xmlns.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| prefix | string | Префикс. |
| namespace_uri | string | URI схемы пакета. |

