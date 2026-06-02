---
title: "EmfExcludeClipRect Класс"
type: docs
weight: 410
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---

**Summary:** The EMR_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing <br/>            clipping region minus the specified rectangle. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExcludeClipRect

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfExcludeClipRect()](#EmfExcludeClipRect__1) | Инициализирует новый экземпляр класса [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/). |
| [EmfExcludeClipRect(source)](#EmfExcludeClipRect_source_2) | Инициализирует новый экземпляр класса [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет клип‑прямоугольник <br/>            в логических единицах. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExcludeClipRect() {#EmfExcludeClipRect__1}


```
 EmfExcludeClipRect() 
```

Инициализирует новый экземпляр класса [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/).

### Constructor: EmfExcludeClipRect(source) {#EmfExcludeClipRect_source_2}


```
 EmfExcludeClipRect(source) 
```

Инициализирует новый экземпляр класса [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/).

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


