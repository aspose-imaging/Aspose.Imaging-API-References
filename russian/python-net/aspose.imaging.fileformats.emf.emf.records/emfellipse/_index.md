---
title: "EmfEllipse Класс"
type: docs
weight: 370
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/
---

**Summary:** The EMR_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified <br/>            bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEllipse

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEllipse()](#EmfEllipse__1) | Инициализирует новый экземпляр класса [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/). |
| [EmfEllipse(source)](#EmfEllipse_source_2) | Инициализирует новый экземпляр класса [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный (WMF) объект RectL, указанный в [MS-WMF] разделе 2.2.2.19, который <br/>            определяет включительно‑включительно ограничивающий прямоугольник. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEllipse() {#EmfEllipse__1}


```
 EmfEllipse() 
```

Инициализирует новый экземпляр класса [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/).

### Constructor: EmfEllipse(source) {#EmfEllipse_source_2}


```
 EmfEllipse(source) 
```

Инициализирует новый экземпляр класса [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/).

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


