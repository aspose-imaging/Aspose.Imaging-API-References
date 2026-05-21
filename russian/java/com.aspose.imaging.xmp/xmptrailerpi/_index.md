---
title: "XmpTrailerPi"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет инструкцию обработки трейлера XMP."
type: docs
weight: 23
url: /ru/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Представляет инструкцию обработки трейлера XMP.

Часть end=\"w\" или end=\"r\" должна использоваться процессорами сканирования пакетов для определения, может ли XMP быть изменён на месте.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Инициализирует новый экземпляр класса `XmpTrailerPi`. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Инициализирует новый экземпляр класса `XmpTrailerPi`. |
## Методы

| Метод | Описание |
| --- | --- |
| [isWritable()](#isWritable--) | Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи. |
| [setWritable(boolean value)](#setWritable-boolean-) | Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение xmp в xml-представление. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `System.Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Инициализирует новый экземпляр класса `XmpTrailerPi`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isWritable | boolean | Указывает, является ли трейлер записываемым. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Инициализирует новый экземпляр класса `XmpTrailerPi`.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи.

Значение: `true`, если этот экземпляр записываемый; в противном случае `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи.

Значение: `true`, если этот экземпляр записываемый; в противном случае `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение xmp в xml-представление.

**Returns:**
java.lang.String - Возвращает XML-представление XMP.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Объект для сравнения с этим объектом. |

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
