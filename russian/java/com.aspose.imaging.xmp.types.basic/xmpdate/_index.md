---
title: "XmpDate"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет дату в пакете XMP."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Представляет дату в пакете XMP.

Значение даты и времени представляется с использованием подмножества форматов, определённых в разделе Форматы даты и времени: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Инициализирует новый экземпляр класса `XmpDate`. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Инициализирует новый экземпляр класса `XmpDate`. |
## Поля

| Поле | Описание |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | Строка формата ISO 8601 (roundtrip). |
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Получает или задает значение даты. |
| [setValue(Date value)](#setValue-java.util.Date-) | Получает или задает значение даты. |
| [getFormat()](#getFormat--) | Получает строку формата для текущего значения. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Возвращает строковое значение в формате XMP. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Инициализирует новый экземпляр класса `XmpDate`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dateTime | java.util.Date | Значение даты и времени, представленное с использованием подмножества формата ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Инициализирует новый экземпляр класса `XmpDate`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dateString | java.lang.String | Строковое представление даты. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


Строка формата ISO 8601 (roundtrip).

Смотрите подробнее: [ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Получает или задает значение даты.

Значение: Значение даты.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Получает или задает значение даты.

Значение: Значение даты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Получает строку формата для текущего значения.

Значение: Строка формата для текущего значения.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Возвращает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строку, содержащую представление xmp
