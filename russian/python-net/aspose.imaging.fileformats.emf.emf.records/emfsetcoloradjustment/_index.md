---
title: "EmfSetColorAdjustment Класс"
type: docs
weight: 1130
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---

**Summary:** The EMR_SETCOLORADJUSTMENT record specifies color adjustment properties in the playback<br/>            device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetColorAdjustment

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetColorAdjustment(source)](#EmfSetColorAdjustment_source_1) | Инициализирует новый экземпляр класса [EmfSetColorAdjustment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_adjustment | [EmfColorAdjustment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/) | r/w | Получает или задаёт объект ColorAdjustment (раздел 2.2.2), который определяет цветовые<br/>            значения коррекции. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetColorAdjustment(source) {#EmfSetColorAdjustment_source_1}


```
 EmfSetColorAdjustment(source) 
```

Инициализирует новый экземпляр класса [EmfSetColorAdjustment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/).

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


