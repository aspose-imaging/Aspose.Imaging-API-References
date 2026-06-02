---
title: "EmfFrameRgn Класс"
type: docs
weight: 530
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/
---

**Summary:** The EMR_FRAMERGN record draws a border around the specified region using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFrameRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfFrameRgn()](#EmfFrameRgn__1) | Инициализирует новый экземпляр класса [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/). |
| [EmfFrameRgn(source)](#EmfFrameRgn_source_2) | Инициализирует новый экземпляр класса [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑разрядный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который <br/>            определяет ограничивающий прямоугольник. |
| height | int | r/w | Получает или задает 32‑разрядное знаковое целое, которое указывает высоту горизонтального штриха кисти <br/>            в логических единицах. |
| ih_brush | int | r/w | Получает или задает 32‑разрядное беззнаковое целое, которое указывает индекс таблицы объектов EMF кисти. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData, <br/>            в логических единицах |
| rgn_data_size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| width | int | r/w | Получает или задает 32‑разрядное знаковое целое, которое указывает ширину вертикального штриха кисти, в логических единицах. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFrameRgn() {#EmfFrameRgn__1}


```
 EmfFrameRgn() 
```

Инициализирует новый экземпляр класса [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/).

### Constructor: EmfFrameRgn(source) {#EmfFrameRgn_source_2}


```
 EmfFrameRgn(source) 
```

Инициализирует новый экземпляр класса [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/).

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


