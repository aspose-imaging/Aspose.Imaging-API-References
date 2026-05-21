---
title: "XmpHeaderPi"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет инструкцию обработки заголовка XMP."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Представляет инструкцию обработки заголовка XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Инициализирует новый экземпляр класса `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Инициализирует новый экземпляр класса `XmpHeaderPi`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getGuid()](#getGuid--) | Представляет GUID заголовка. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Представляет GUID заголовка. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в XML-представление. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `System.Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Инициализирует новый экземпляр класса `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Инициализирует новый экземпляр класса `XmpHeaderPi`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| guid | java.lang.String | Уникальный идентификатор. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Представляет GUID заголовка.

Текст заголовка PI содержит GUID, что делает его маловероятным для случайного появления в потоке данных.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Представляет GUID заголовка.

Текст заголовка PI содержит GUID, что делает его маловероятным для случайного появления в потоке данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение XMP в XML-представление.

**Returns:**
java.lang.String — Возвращает значение XMP, преобразованное в XML-представление.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру `other`; в противном случае false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный `System.Object` этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для сравнения с этим экземпляром. |

**Returns:**
boolean - `true`, если указанный `System.Object` равен этому экземпляру; иначе `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
