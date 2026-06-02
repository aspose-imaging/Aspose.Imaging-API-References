---
title: "Класс EmfPolyPolyline16"
type: docs
weight: 860
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/
---

**Summary:** The EMR_POLYPOLYLINE16 record specifies multiple series of connected line segments.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolyline16

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyPolyline16()](#EmfPolyPolyline16__1) | Инициализирует новый экземпляр класса [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/). |
| [EmfPolyPolyline16(source)](#EmfPolyPolyline16_source_2) | Инициализирует новый экземпляр класса [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Получает или задает массив объектов WMF PointS, указанных в [MS-WMF] <br/>            раздел 2.2.2.16, который определяет массив точек. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyPolyline16() {#EmfPolyPolyline16__1}


```
 EmfPolyPolyline16() 
```

Инициализирует новый экземпляр класса [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/).

### Constructor: EmfPolyPolyline16(source) {#EmfPolyPolyline16_source_2}


```
 EmfPolyPolyline16(source) 
```

Инициализирует новый экземпляр класса [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/).

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


