---
title: "EmfCreateColorSpace Класс"
type: docs
weight: 270
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---

**Summary:** The EMR_CREATECOLORSPACE record creates a logical color space object from a color profile with a<br/>            name consisting of ASCII characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpace

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreateColorSpace(source)](#EmfCreateColorSpace_source_1) | Инициализирует новый экземпляр класса [EmfCreateColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_cs | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает индекс логического цветового пространства<br/> объекта в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект<br/> мог быть повторно использован или изменён. |
| lcs | [WmfLogColorSpace](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) | r/w | Получает или задает объект WMF LogColorSpace ([MS-WMF] раздел 2.2.2.11), который может указывать<br/> имя цветового профиля в символах ASCII. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateColorSpace(source) {#EmfCreateColorSpace_source_1}


```
 EmfCreateColorSpace(source) 
```

Инициализирует новый экземпляр класса [EmfCreateColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/).

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


