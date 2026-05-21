---
title: "XmpRdfRoot"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет элемент rdfRDF."
type: docs
weight: 22
url: /ru/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Представляет элемент rdf:RDF. Один пакет XMP должен сериализоваться с использованием единственного XML‑элемента rdf:RDF. Содержание элемента rdf:RDF должно состоять только из нуля или более элементов rdf:Description.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Инициализирует новый экземпляр класса `XmpRdfRoot`. |
## Методы

| Метод | Описание |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Добавляет URI пространства имён по префиксу. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Получает URI пространства имён по конкретному префиксу. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение xmp в xml-представление. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Инициализирует новый экземпляр класса `XmpRdfRoot`.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Добавляет URI пространства имён по префиксу. Префикс может начинаться без xmlns.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | java.lang.String | Префикс. |
| namespaceUri | java.lang.String | URI схемы пакета. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Получает URI пространства имён по конкретному префиксу. Префикс может начинаться без xmlns.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | java.lang.String | Префикс. |

**Returns:**
java.lang.String - Возвращает URI схемы пакета.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение xmp в xml-представление.

**Returns:**
java.lang.String - Возвращает значение XMP, преобразованное в строку XML.
