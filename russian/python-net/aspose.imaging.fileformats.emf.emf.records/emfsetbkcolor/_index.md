---
title: "Класс EmfSetBkColor"
type: docs
weight: 1100
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/
---

**Summary:** The EMR_SETBKCOLOR record specifies the background color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBkColor

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetBkColor()](#EmfSetBkColor__1) | Инициализирует новый экземпляр класса [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/). |
| [EmfSetBkColor(source)](#EmfSetBkColor_source_2) | Инициализирует новый экземпляр класса [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Получает или задает 32‑битный объект WMF ColorRef, указанный в [MS-WMF] разделе 2.2.2.8, который<br/>            определяет значение фонового цвета. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetBkColor() {#EmfSetBkColor__1}


```
 EmfSetBkColor() 
```

Инициализирует новый экземпляр класса [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/).

### Constructor: EmfSetBkColor(source) {#EmfSetBkColor_source_2}


```
 EmfSetBkColor(source) 
```

Инициализирует новый экземпляр класса [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/).

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


