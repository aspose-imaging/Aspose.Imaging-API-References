---
title: "Timecode Класс"
type: docs
weight: 60
url: /ru/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/
---

**Summary:** Represents timecode value in video.

**Module:** [aspose.imaging.xmp.schemas.xmpdm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpdm.Timecode

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Timecode(format, time_value)](#Timecode_format_time_value_1) | Инициализирует новый экземпляр класса [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | r/w | Получает или задает формат, используемый в [Timecode.time_value](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/). |
| time_value | string | r/w | Получает или задает значение времени в указанном формате. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |
| [get_xmp_representation()](#get_xmp_representation__2) | Возвращает строковое значение в формате XMP. |


### Constructor: Timecode(format, time_value) {#Timecode_format_time_value_1}


```
 Timecode(format, time_value) 
```

Инициализирует новый экземпляр класса [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | Формат времени. |
| time_value | string | Значение времени. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object | Клонирование по членам. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Возвращает строковое значение в формате XMP.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает строку, содержащую представление xmp. |


