---
title: "Класс XmpDate"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Инициализирует новый экземпляр класса [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) . |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Инициализирует новый экземпляр класса [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | Строка формата ISO 8601 (roundtrip). |
| format | string | r | Получает строку формата для текущего значения. |
| значение | System.DateTime | r/w | Получает или задает значение даты. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |
| [get_xmp_representation()](#get_xmp_representation__2) | Возвращает строковое значение в формате XMP. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Инициализирует новый экземпляр класса [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| date_string | string | Строковое представление даты. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Инициализирует новый экземпляр класса [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| дата_время | System.DateTime | Значение даты и времени, представленное с использованием подмножества формата ISO RFC 8601. |

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


