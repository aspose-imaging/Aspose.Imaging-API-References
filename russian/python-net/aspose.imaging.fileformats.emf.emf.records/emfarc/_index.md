---
title: "Класс EmfArc"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | Инициализирует новый экземпляр класса [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
| [EmfArc(source)](#EmfArc_source_2) | Инициализирует новый экземпляр класса [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который <br/>            определяет включительно‑включительный ограничивающий прямоугольник. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64‑битный объект WMF PointL, который определяет координаты, в логических единицах, <br/>            конечной точки радиальной линии, определяющей конечную точку дуги. |
| size | int | r/w | Получает или задает размер записи |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который <br/>            определяет координаты, в логических единицах, конечной точки радиальной линии, определяющей <br/>            начальную точку дуги. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

Инициализирует новый экземпляр класса [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

Инициализирует новый экземпляр класса [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

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


