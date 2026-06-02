---
title: "Класс EmfSetPolyFillMode"
type: docs
weight: 1270
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---

**Summary:** The EMR_SETPOLYFILLMODE record defines polygon fill mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPolyFillMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode__1) | Инициализирует новый экземпляр класса [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/). |
| [EmfSetPolyFillMode(source)](#EmfSetPolyFillMode_source_2) | Инициализирует новый экземпляр класса [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| polygon_fill_mode | [EmfPolygonFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpolygonfillmode/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет режим заливки полигона и<br/>            ДОЛЖНО находиться в перечислении PolygonFillMode (раздел 2.1.27). |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetPolyFillMode() {#EmfSetPolyFillMode__1}


```
 EmfSetPolyFillMode() 
```

Инициализирует новый экземпляр класса [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/).

### Constructor: EmfSetPolyFillMode(source) {#EmfSetPolyFillMode_source_2}


```
 EmfSetPolyFillMode(source) 
```

Инициализирует новый экземпляр класса [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/).

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


