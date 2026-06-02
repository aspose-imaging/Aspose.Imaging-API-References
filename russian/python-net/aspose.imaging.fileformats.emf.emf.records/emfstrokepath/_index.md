---
title: "EmfStrokePath Класс"
type: docs
weight: 1430
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokepath/
---

**Summary:** EMR_STROKEPATH class

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStrokePath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStrokePath()](#EmfStrokePath__1) | Инициализирует новый экземпляр класса [EmfStrokePath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokepath/). |
| [EmfStrokePath(record)](#EmfStrokePath_record_2) | Инициализирует новый экземпляр класса [EmfStrokePath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokepath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStrokePath() {#EmfStrokePath__1}


```
 EmfStrokePath() 
```

Инициализирует новый экземпляр класса [EmfStrokePath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokepath/).

### Constructor: EmfStrokePath(record) {#EmfStrokePath_record_2}


```
 EmfStrokePath(record) 
```

Инициализирует новый экземпляр класса [EmfStrokePath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokepath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Запись. |

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


