---
title: "Класс EmfSetViewportOrgEx"
type: docs
weight: 1340
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/
---

**Summary:** The EMR_SETVIEWPORTORGEX record defines the viewport origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetViewportOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetViewportOrgEx()](#EmfSetViewportOrgEx__1) | Инициализирует новый экземпляр класса [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/). |
| [EmfSetViewportOrgEx(source)](#EmfSetViewportOrgEx_source_2) | Инициализирует новый экземпляр класса [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64-битный объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет<br/>            горизонтальное и вертикальное начало окна в единицах устройства. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetViewportOrgEx() {#EmfSetViewportOrgEx__1}


```
 EmfSetViewportOrgEx() 
```

Инициализирует новый экземпляр класса [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/).

### Constructor: EmfSetViewportOrgEx(source) {#EmfSetViewportOrgEx_source_2}


```
 EmfSetViewportOrgEx(source) 
```

Инициализирует новый экземпляр класса [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/).

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


