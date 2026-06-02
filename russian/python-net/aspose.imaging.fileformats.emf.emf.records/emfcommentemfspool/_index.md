---
title: "Класс EmfCommentEmfSpool"
type: docs
weight: 190
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---

**Summary:** The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfSpool

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool__1) | Инициализирует новый экземпляр класса [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/). |
| [EmfCommentEmfSpool(source)](#EmfCommentEmfSpool_source_2) | Инициализирует новый экземпляр класса [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет эту запись комментария <br/>            как содержащую записи EMFSPOOL. Значение 0x00000000 определяет её как запись <br/>            EMR_COMMENT_EMFSPOOL. |
| data_size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает размер в байтах полей <br/>            CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое <br/>            следует. Оно НЕ ДОЛЖНО включать размер самого себя или размер поля AlignmentPadding, если <br/>            оно присутствует. |
| emf_spool_record_identifier | [EmfCommentEmfSpool+EmfSpoolRecordIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool+emfspoolrecordidentifierenum/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет тип <br/>            записи EMR_COMMENT_EMFSPOOL. |
| emf_spool_records | [EmfSpoolFontDefinitionRecordType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype/) | r/w | Получает или задает переменного размера массив байтов, содержащий одну или несколько <br/>            записей определения шрифтов EMFSPOOL ([MS-EMFSPOOL] раздел 2.2.3.3). |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentEmfSpool() {#EmfCommentEmfSpool__1}


```
 EmfCommentEmfSpool() 
```

Инициализирует новый экземпляр класса [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/).

### Constructor: EmfCommentEmfSpool(source) {#EmfCommentEmfSpool_source_2}


```
 EmfCommentEmfSpool(source) 
```

Инициализирует новый экземпляр класса [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/).

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


