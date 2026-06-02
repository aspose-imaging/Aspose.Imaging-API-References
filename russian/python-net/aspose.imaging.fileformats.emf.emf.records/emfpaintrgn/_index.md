---
title: "Класс EmfPaintRgn"
type: docs
weight: 710
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---

**Summary:** The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the <br/>            playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPaintRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPaintRgn()](#EmfPaintRgn__1) | Инициализирует новый экземпляр класса [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/). |
| [EmfPaintRgn(source)](#EmfPaintRgn_source_2) | Инициализирует новый экземпляр класса [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, <br/>            который определяет ограничивающий прямоугольник. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData (раздел <br/>            2.2.24) в логических единицах. |
| rgn_data_size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPaintRgn() {#EmfPaintRgn__1}


```
 EmfPaintRgn() 
```

Инициализирует новый экземпляр класса [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/).

### Constructor: EmfPaintRgn(source) {#EmfPaintRgn_source_2}


```
 EmfPaintRgn(source) 
```

Инициализирует новый экземпляр класса [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/).

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


