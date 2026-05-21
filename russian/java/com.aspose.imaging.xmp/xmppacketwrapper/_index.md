---
title: "XmpPacketWrapper"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Содержит сериализованный пакет xmp, включающий заголовок и трейлер."
type: docs
weight: 21
url: /ru/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Содержит сериализованный пакет xmp, включающий заголовок и трейлер.

Обёртка, состоящая из пары инструкций обработки XML (PI), может быть размещена вокруг элемента rdf:RDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | Инициализирует новый экземпляр класса `XmpPacketWrapper`. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Инициализирует новый экземпляр класса `XmpPacketWrapper`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Получает инструкцию обработки заголовка. |
| [getMeta()](#getMeta--) | Получает метаданные XMP. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | Устанавливает метаданные XMP. |
| [getTrailerPi()](#getTrailerPi--) | Получает инструкцию обработки трейлера. |
| [getPackages()](#getPackages--) | Получает массив `XmpPackage` внутри XMP. |
| [getPackagesCount()](#getPackagesCount--) | Получает количество пакетов внутри структуры XMP. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Добавляет пакет. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Получает пакет по URI пространства имён. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Определяет, существует ли пакет в обёртке XMP. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | Удаляет пакет XMP. |
| [clearPackages()](#clearPackages--) | Удаляет все `XmpPackage` внутри XMP. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в XML-представление. |
| [toString()](#toString--) | Возвращает строку XML, представляющую текущий объект. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Инициализирует новый экземпляр класса `XmpPacketWrapper`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Заголовок XMP инструкции обработки. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Трейлер XMP инструкции обработки. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Метаданные XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Инициализирует новый экземпляр класса `XmpPacketWrapper`.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Получает инструкцию обработки заголовка.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Получает метаданные XMP. Необязательно.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Устанавливает метаданные XMP. Необязательно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Метаданные XMP. Необязательно. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Получает инструкцию обработки трейлера.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Получает массив `XmpPackage` внутри XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Массив `XmpPackage` внутри XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Получает количество пакетов внутри структуры XMP.

**Returns:**
int - Количество пакетов внутри структуры XMP.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Добавляет пакет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Пакет. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Получает пакет по URI пространства имён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI схемы пакета. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Определяет, существует ли пакет в обёртке XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI схемы пакета. |

**Returns:**
boolean - Возвращает true, если пакет с указанным URI пространства имён существует в обёртке XMP.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Удаляет пакет XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Пакет. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Удаляет все `XmpPackage` внутри XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение XMP в XML-представление.

**Returns:**
java.lang.String - Возвращает преобразованное значение XMP в XML.
### toString() {#toString--}
```
public String toString()
```


Возвращает строку XML, представляющую текущий объект.

**Returns:**
java.lang.String - Строка XML, представляющая текущий объект.
