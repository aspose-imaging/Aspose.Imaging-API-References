---
title: "EmfSetArcDirection Класс"
type: docs
weight: 1090
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---

**Summary:** The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetArcDirection

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetArcDirection()](#EmfSetArcDirection__1) | Инициализирует новый экземпляр класса [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
| [EmfSetArcDirection(source)](#EmfSetArcDirection_source_2) | Инициализирует новый экземпляр класса [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| arc_direction | [EmfArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfarcdirection/) | r/w | Получает или задает 32‑разрядное беззнаковое целое, которое указывает направление дуги. Значение<br/>            ДОЛЖНО быть в перечислении ArcDirection (раздел 2.1.2).<br/>            Направление по умолчанию — против часовой стрелки. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetArcDirection() {#EmfSetArcDirection__1}


```
 EmfSetArcDirection() 
```

Инициализирует новый экземпляр класса [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

### Constructor: EmfSetArcDirection(source) {#EmfSetArcDirection_source_2}


```
 EmfSetArcDirection(source) 
```

Инициализирует новый экземпляр класса [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

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


