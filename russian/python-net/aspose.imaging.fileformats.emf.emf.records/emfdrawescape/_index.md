---
title: "Класс EmfDrawEscape"
type: docs
weight: 350
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---

**Summary:** The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will result in drawing being done.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDrawEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfDrawEscape(source)](#EmfDrawEscape_source_1) | Инициализирует новый экземпляр класса [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cj_in | int | r/w | Получает или задает 32‑битное беззнаковое целое, указывающее количество байтов, передаваемых драйверу принтера. |
| данные | System.Byte | r/w | Получает или задает данные, передаваемые драйверу принтера. Должно быть доступно cjIn байт. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет escape драйвера принтера для<br/>            выполнения. Это ДОЛЖНО быть одним из значений в перечислении WMF MetafileEscapes ([MSWMF] раздел 2.1.1.17). |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfDrawEscape(source) {#EmfDrawEscape_source_1}


```
 EmfDrawEscape(source) 
```

Инициализирует новый экземпляр класса [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/).

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


