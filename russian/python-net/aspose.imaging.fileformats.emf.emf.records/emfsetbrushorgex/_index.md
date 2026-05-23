---
title: "Класс EmfSetBrushOrgEx"
type: docs
weight: 1120
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---

**Summary:** The EMR_SETBRUSHORGEX record specifies the origin of the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBrushOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx__1) | Инициализирует новый экземпляр класса [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/). |
| [EmfSetBrushOrgEx(source)](#EmfSetBrushOrgEx_source_2) | Инициализирует новый экземпляр класса [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64-битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который<br/>            определяет горизонтальное и вертикальное начало кисти в единицах устройства. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetBrushOrgEx() {#EmfSetBrushOrgEx__1}


```
 EmfSetBrushOrgEx() 
```

Инициализирует новый экземпляр класса [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/).

### Constructor: EmfSetBrushOrgEx(source) {#EmfSetBrushOrgEx_source_2}


```
 EmfSetBrushOrgEx(source) 
```

Инициализирует новый экземпляр класса [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/).

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


