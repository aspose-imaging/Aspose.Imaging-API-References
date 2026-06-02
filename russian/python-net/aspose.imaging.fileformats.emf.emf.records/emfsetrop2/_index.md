---
title: "EmfSetRop2 Класс"
type: docs
weight: 1280
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---

**Summary:** The EMR_SETROP2 record defines a binary raster operation mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetRop2

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetRop2()](#EmfSetRop2__1) | Инициализирует новый экземпляр класса [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/). |
| [EmfSetRop2(source)](#EmfSetRop2_source_2) | Инициализирует новый экземпляр класса [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| rop_2_mode | [WmfBinaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет режим растровой операции и<br/>            ДОЛЖНО находиться в перечислении WMF Binary Raster Op ([MS-WMF] раздел 2.1.1.2). |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetRop2() {#EmfSetRop2__1}


```
 EmfSetRop2() 
```

Инициализирует новый экземпляр класса [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/).

### Constructor: EmfSetRop2(source) {#EmfSetRop2_source_2}


```
 EmfSetRop2(source) 
```

Инициализирует новый экземпляр класса [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/).

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


