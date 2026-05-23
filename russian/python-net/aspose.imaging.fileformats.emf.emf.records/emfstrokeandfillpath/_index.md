---
title: "EmfStrokeAndFillPath Класс"
type: docs
weight: 1420
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/
---

**Summary:** The EMR_STROKEANDFILLPATH record closes any open figures in a path, strokes the outline of the<br/>            path by using the current pen, and fills its interior by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStrokeAndFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStrokeAndFillPath()](#EmfStrokeAndFillPath__1) | Инициализирует новый экземпляр класса [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/). |
| [EmfStrokeAndFillPath(source)](#EmfStrokeAndFillPath_source_2) | Инициализирует новый экземпляр класса [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет<br/>            ограничивающий прямоугольник в единицах устройства. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStrokeAndFillPath() {#EmfStrokeAndFillPath__1}


```
 EmfStrokeAndFillPath() 
```

Инициализирует новый экземпляр класса [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/).

### Constructor: EmfStrokeAndFillPath(source) {#EmfStrokeAndFillPath_source_2}


```
 EmfStrokeAndFillPath(source) 
```

Инициализирует новый экземпляр класса [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/).

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


