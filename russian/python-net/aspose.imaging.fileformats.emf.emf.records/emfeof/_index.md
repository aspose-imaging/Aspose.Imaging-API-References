---
title: "Класс EmfEof"
type: docs
weight: 390
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | Инициализирует новый экземпляр класса [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
| [EmfEof(record)](#EmfEof_record_2) | Инициализирует новый экземпляр класса [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | Получает или задает необязательный буфер, содержащий данные палитры, который не <br/>            обязан быть смежным с фиксированной частью записи EMR_EOF <br/>            . Соответственно, поля в этом буфере, помеченные <br/>            "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. <br/>            Размер этого поля ДОЛЖЕН быть кратным 4 байтам |
| size | int | r/w | Получает или задает размер записи |
| size_last | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое ДОЛЖНО быть одинаковым с Size и ДОЛЖНО быть последним <br/>            полем записи, а следовательно и метафайла. Объекты LogPaletteEntry, если они <br/>            существуют, ДОЛЖНЫ предшествовать этому полю. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Инициализирует новый экземпляр класса [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

Инициализирует новый экземпляр класса [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

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


