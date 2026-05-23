---
title: "Класс XmpPacketWrapper"
type: docs
weight: 480
url: /ru/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Инициализирует новый экземпляр класса [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Инициализирует новый экземпляр класса [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Получает инструкцию обработки заголовка. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | Получает метаданные XMP. Необязательно. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | Получает массив [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) внутри XMP. |
| packages_count | int | r | Получает количество пакетов внутри структуры XMP. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | Получает инструкцию обработки трейлера. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Добавляет пакет. |
| clear_packages() | Удаляет все [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) внутри XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Определяет, существует ли пакет в обёртке xmp. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Получает пакет по URI пространства имён. |
| [get_xml_value()](#get_xml_value__4) | Преобразует значение XMP в XML‑представление. |
| [remove_package(package)](#remove_package_package_5) | Удаляет пакет XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Инициализирует новый экземпляр класса [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Инициализирует новый экземпляр класса [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | Заголовок XMP инструкции обработки. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | Трейлер XMP инструкции обработки. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | Метаданные XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Добавляет пакет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Пакет. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Определяет, существует ли пакет в обёртке xmp.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| namespace_uri | string | URI схемы пакета. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Возвращает true, если пакет с указанным URI пространства имён существует в обёртке XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Получает пакет по URI пространства имён.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| namespace_uri | string | URI схемы пакета. |

**Returns**

| Тип | Описание |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Возвращает пакет XMP для указанного URI пространства имён. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Преобразует значение XMP в XML‑представление.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает преобразованное значение XMP в XML. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Удаляет пакет XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Пакет. |

