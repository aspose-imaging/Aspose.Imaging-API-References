---
title: "EmfCreatePen Класс"
type: docs
weight: 320
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---

**Summary:** The EMR_CREATEPEN record defines a logical pen for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreatePen()](#EmfCreatePen__1) | Инициализирует новый экземпляр класса [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/). |
| [EmfCreatePen(source)](#EmfCreatePen_source_2) | Инициализирует новый экземпляр класса [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_pen | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет индекс логического объекта пера в<br/>            таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект мог быть<br/>            повторно использован или изменён. |
| log_pen | [EmfLogPen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpen/) | r/w | Получает или задает объект LogPen (раздел 2.2.19), который определяет стиль, ширину и цвет<br/>            логического пера. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreatePen() {#EmfCreatePen__1}


```
 EmfCreatePen() 
```

Инициализирует новый экземпляр класса [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/).

### Constructor: EmfCreatePen(source) {#EmfCreatePen_source_2}


```
 EmfCreatePen(source) 
```

Инициализирует новый экземпляр класса [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/).

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


