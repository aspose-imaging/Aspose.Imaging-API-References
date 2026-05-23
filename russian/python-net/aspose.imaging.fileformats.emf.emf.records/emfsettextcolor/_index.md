---
title: "EmfSetTextColor Класс"
type: docs
weight: 1310
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/
---

**Summary:** The EMR_SETTEXTCOLOR record defines the current text color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextColor

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetTextColor()](#EmfSetTextColor__1) | Инициализирует новый экземпляр класса [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/). |
| [EmfSetTextColor(source)](#EmfSetTextColor_source_2) | Инициализирует новый экземпляр класса [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который указывает значение цвета текста. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetTextColor() {#EmfSetTextColor__1}


```
 EmfSetTextColor() 
```

Инициализирует новый экземпляр класса [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/).

### Constructor: EmfSetTextColor(source) {#EmfSetTextColor_source_2}


```
 EmfSetTextColor(source) 
```

Инициализирует новый экземпляр класса [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Тип записи. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


