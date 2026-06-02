---
title: "XmpMeta"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет метаданные xmp."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Представляет xmp meta. Необязательно. Цель этого элемента — идентифицировать XMP‑метаданные в общем XML‑тексте, который может содержать другие не‑XMP использования RDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Инициализирует новый экземпляр класса `XmpMeta`. |
| [XmpMeta()](#XmpMeta--) | Инициализирует новый экземпляр класса `XmpMeta`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Получает или задает версию набора инструментов Adobe Xmp. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Получает или задает версию набора инструментов Adobe Xmp. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Добавляет атрибут. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в XML-представление. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object other)](#equals-java.lang.Object-) | Определяет, равен ли указанный `System.Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Инициализирует новый экземпляр класса `XmpMeta`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Версия набора инструментов Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Инициализирует новый экземпляр класса `XmpMeta`.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Получает или задает версию набора инструментов Adobe Xmp.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Получает или задает версию набора инструментов Adobe Xmp.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Добавляет атрибут.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| атрибут | java.lang.String | Атрибут. |
| value | java.lang.String | Значение. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение XMP в XML-представление.

**Returns:**
java.lang.String — Возвращает значение XMP, преобразованное в XML-представление.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру `other`; в противном случае false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Определяет, равен ли указанный `System.Object` этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| другой | java.lang.Object | Объект `System.Object` для сравнения с этим экземпляром. |

**Returns:**
boolean - `true`, если указанный `System.Object` равен этому экземпляру; иначе `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
