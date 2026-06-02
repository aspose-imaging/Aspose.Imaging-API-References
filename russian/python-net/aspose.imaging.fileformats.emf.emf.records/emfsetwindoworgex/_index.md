---
title: "Класс EmfSetWindowOrgEx"
type: docs
weight: 1360
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/
---

**Summary:** The EMR_SETWINDOWORGEX record defines the window origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWindowOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetWindowOrgEx()](#EmfSetWindowOrgEx__1) | Инициализирует новый экземпляр класса [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) class. |
| [EmfSetWindowOrgEx(source)](#EmfSetWindowOrgEx_source_2) | Инициализирует новый экземпляр класса [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64-битный объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который указывает<br/>            горизонтальное и вертикальное начало окна в логических единицах. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWindowOrgEx() {#EmfSetWindowOrgEx__1}


```
 EmfSetWindowOrgEx() 
```

Инициализирует новый экземпляр класса [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) class.

### Constructor: EmfSetWindowOrgEx(source) {#EmfSetWindowOrgEx_source_2}


```
 EmfSetWindowOrgEx(source) 
```

Инициализирует новый экземпляр класса [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) class.

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


