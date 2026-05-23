---
title: "Класс EmfSetWindowExtEx"
type: docs
weight: 1350
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/
---

**Summary:** The EMR_SETWINDOWEXTEX record defines the window extent.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWindowExtEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetWindowExtEx()](#EmfSetWindowExtEx__1) | Инициализирует новый экземпляр класса [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/). |
| [EmfSetWindowExtEx(source)](#EmfSetWindowExtEx_source_2) | Инициализирует новый экземпляр класса [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| extent | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Получает или задает 64-битный объект WMF SizeL ([MS-WMF] раздел 2.2.2.22), который определяет<br/>            горизонтальные и вертикальные размеры в логических единицах. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWindowExtEx() {#EmfSetWindowExtEx__1}


```
 EmfSetWindowExtEx() 
```

Инициализирует новый экземпляр класса [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/).

### Constructor: EmfSetWindowExtEx(source) {#EmfSetWindowExtEx_source_2}


```
 EmfSetWindowExtEx(source) 
```

Инициализирует новый экземпляр класса [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/).

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


