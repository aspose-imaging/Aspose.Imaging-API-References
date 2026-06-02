---
title: "EmfSetPaletteEntries Класс"
type: docs
weight: 1250
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---

**Summary:** The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing<br/>            LogPalette (section 2.2.17) object.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPaletteEntries

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetPaletteEntries(source)](#EmfSetPaletteEntries_source_1) | Инициализирует новый экземпляр класса [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_pal_entries | int[] | r/w | Получает или задает массив объектов LogPaletteEntry (раздел 2.2.18) длиной <br/>            NumberOfEntries, который определяет данные записей палитры. Члены Values не содержат никаких значений. |
| ih_pal | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает индекс таблицы объектов EMF палитры. |
| numberof_entries | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает количество записей. |
| size | int | r/w | Получает или задает размер записи |
| начало | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает индекс первой записи для установки. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetPaletteEntries(source) {#EmfSetPaletteEntries_source_1}


```
 EmfSetPaletteEntries(source) 
```

Инициализирует новый экземпляр класса [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/).

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


