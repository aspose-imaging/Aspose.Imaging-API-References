---
title: "EmfRectangle Класс"
type: docs
weight: 980
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---

**Summary:** The EMR_RECTANGLE record draws a rectangle. The rectangle is outlined by using the current pen<br/>            and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRectangle

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRectangle()](#EmfRectangle__1) | Инициализирует новый экземпляр класса [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/). |
| [EmfRectangle(source)](#EmfRectangle_source_2) | Инициализирует новый экземпляр класса [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL, указанный в разделе [MS-WMF] 2.2.2.19, который <br/>            определяет включительно‑включительный прямоугольник для рисования. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRectangle() {#EmfRectangle__1}


```
 EmfRectangle() 
```

Инициализирует новый экземпляр класса [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/).

### Constructor: EmfRectangle(source) {#EmfRectangle_source_2}


```
 EmfRectangle(source) 
```

Инициализирует новый экземпляр класса [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/).

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


