---
title: "Timecode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет значение таймкода в видео."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Представляет значение таймкода в видео.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Инициализирует новый экземпляр класса `Timecode`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) | Получает или задает формат, используемый в `TimeValue`. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | Получает или задает формат, используемый в `TimeValue`. |
| [getTimeValue()](#getTimeValue--) | Получает или задает значение времени в указанном формате. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Получает или задает значение времени в указанном формате. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Возвращает строковое значение в формате XMP. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `System.Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Инициализирует новый экземпляр класса `Timecode`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | Формат времени. |
| timeValue | java.lang.String | Значение времени. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Получает или задает формат, используемый в `TimeValue`.

Значение: Формат, используемый в `TimeValue`.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Получает или задает формат, используемый в `TimeValue`.

Значение: Формат, используемый в `TimeValue`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Получает или задает значение времени в указанном формате.

Значение: Значение времени в указанном формате.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Получает или задает значение времени в указанном формате.

Значение: Значение времени в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Возвращает строковое значение в формате XMP.

**Returns:**
java.lang.String — Возвращает строку, содержащую представление xmp.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | Объект для сравнения с этим объектом. |

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
