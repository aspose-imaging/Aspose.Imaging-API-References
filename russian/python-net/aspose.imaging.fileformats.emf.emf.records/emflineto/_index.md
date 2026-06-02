---
title: "EmfLineTo Класс"
type: docs
weight: 590
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/
---

**Summary:** The EMR_LINETO record specifies a line from the current position up to, but not including, the<br/>            specified point.It resets the current position to the specified point.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfLineTo

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLineTo()](#EmfLineTo__1) | Инициализирует новый экземпляр класса [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/). |
| [EmfLineTo(record)](#EmfLineTo_record_2) | Инициализирует новый экземпляр класса [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64-битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, <br/>            который определяет координаты конечной точки линии. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfLineTo() {#EmfLineTo__1}


```
 EmfLineTo() 
```

Инициализирует новый экземпляр класса [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/).

### Constructor: EmfLineTo(record) {#EmfLineTo_record_2}


```
 EmfLineTo(record) 
```

Инициализирует новый экземпляр класса [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/).

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


