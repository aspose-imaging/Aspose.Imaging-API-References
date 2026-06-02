---
title: "EmfCreateColorSpaceW Класс"
type: docs
weight: 280
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---

**Summary:** The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with<br/>            a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpaceW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreateColorSpaceW(source)](#EmfCreateColorSpaceW_source_1) | Инициализирует новый экземпляр класса [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает размер в байтах поля Data. |
| данные | System.Byte | r/w | Получает или задает необязательный массив байтов, содержащий данные цветового профиля. |
| dw_flags | int | r/w | Получает или задает 32-битное беззнаковое целое, предоставляющее информацию о данных в этой записи. |
| ih_cs | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает индекс логического цветового пространства<br/> объекта в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект<br/> мог быть повторно использован или изменён. |
| lcs | [WmfLogColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) | r/w | Получает или задает объект WMF LogColorSpaceW ([MS-WMF] section 2.2.2.12), который может указывать<br/>            имя цветового профиля в символах Unicode UTF16-LE. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateColorSpaceW(source) {#EmfCreateColorSpaceW_source_1}


```
 EmfCreateColorSpaceW(source) 
```

Инициализирует новый экземпляр класса [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/).

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


