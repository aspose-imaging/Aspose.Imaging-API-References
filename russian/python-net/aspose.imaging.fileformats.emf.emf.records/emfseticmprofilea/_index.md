---
title: "Класс EmfSetIcmProfileA"
type: docs
weight: 1170
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---

**Summary:** The EMR_SETICMPROFILEA record specifies a color profile in a file with a name consisting of ASCII<br/>            characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileA

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetIcmProfileA(source)](#EmfSetIcmProfileA_source_1) | Инициализирует новый экземпляр класса [EmfSetIcmProfileA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает размер данных цветового профиля, если он<br/>            содержится в поле Data. |
| cb_name | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает количество байт в ASCII<br/>            имени требуемого цветового профиля. |
| данные | System.Byte | r/w | Получает или задает массив размером (cbName + cbData) в байтах, который содержит ASCII<br/>            имя и необработанные данные требуемого цветового профиля. |
| dw_flags | int | r/w | Получает или задает 32-битное беззнаковое целое, содержащее флаги цветового профиля. |
| имя | string | r | Получает имя |
| raw_data | System.Byte | r | Получает необработанные данные |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetIcmProfileA(source) {#EmfSetIcmProfileA_source_1}


```
 EmfSetIcmProfileA(source) 
```

Инициализирует новый экземпляр класса [EmfSetIcmProfileA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/).

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


