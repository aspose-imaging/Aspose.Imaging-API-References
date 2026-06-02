---
title: "EmfPolyDraw Класс"
type: docs
weight: 800
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---

**Summary:** The EMR_POLYDRAW record specifies a set of line segments and Bezier curves.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyDraw

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyDraw()](#EmfPolyDraw__1) | Инициализирует новый экземпляр класса [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/). |
| [EmfPolyDraw(source)](#EmfPolyDraw_source_2) | Инициализирует новый экземпляр класса [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает массив объектов WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет данные точек в логических единицах. |
| ab_types | [EmfPointEnum[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/) | r/w | Получает или задает массив байтов длиной Count, который определяет, как используется каждая точка в массиве <br/>            aPoints. Это значение ДОЛЖНО соответствовать перечислению Point (раздел 2.1.26). |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyDraw() {#EmfPolyDraw__1}


```
 EmfPolyDraw() 
```

Инициализирует новый экземпляр класса [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/).

### Constructor: EmfPolyDraw(source) {#EmfPolyDraw_source_2}


```
 EmfPolyDraw(source) 
```

Инициализирует новый экземпляр класса [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/).

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


