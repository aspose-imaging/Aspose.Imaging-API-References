---
title: "Класс EmfNamedEscape"
type: docs
weight: 660
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---

**Summary:** The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfNamedEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfNamedEscape(source)](#EmfNamedEscape_source_1) | Инициализирует новый экземпляр класса [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cj_driver | int | r/w | Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество байтов в поле <br/>            DriverName. Это значение ДОЛЖНО быть чётным. |
| cj_in | int | r/w | Получает или задаёт 32‑битное беззнаковое целое, определяющее количество байтов, передаваемых драйверу принтера. |
| данные | System.Byte | r/w | Получает или задаёт данные, передаваемые драйверу принтера. ДОЛЖНО быть доступно cjIn байтов. |
| driver_name | string | r/w | Получает или задает строку из 16‑битных символов Unicode, которая указывает имя<br/>драйвера принтера, получающего данные. Это значение ДОЛЖНО быть длиной cjDriver байт и ДОЛЖНО быть<br/>завершено нулевым символом. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет escape драйвера принтера для<br/>            выполнения. Это ДОЛЖНО быть одним из значений в перечислении WMF MetafileEscapes ([MSWMF] раздел 2.1.1.17). |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfNamedEscape(source) {#EmfNamedEscape_source_1}


```
 EmfNamedEscape(source) 
```

Инициализирует новый экземпляр класса [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/).

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


