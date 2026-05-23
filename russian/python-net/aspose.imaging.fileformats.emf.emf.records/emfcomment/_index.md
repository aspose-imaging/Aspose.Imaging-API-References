---
title: "Класс EmfComment"
type: docs
weight: 160
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---

**Summary:** The EMR_COMMENT record contains arbitrary private data.<br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfComment

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfComment(source)](#EmfComment_source_1) | Инициализирует новый экземпляр класса [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Получает или задает идентификатор комментария. |
| data_size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает размер в байтах полей <br/>            CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое <br/>            следует. Оно НЕ ДОЛЖНО включать размер самого себя или размер поля AlignmentPadding, если <br/>            оно присутствует. |
| private_data | System.Byte | r/w | Получает или задает необязательный массив байтов, который определяет закрытые данные. Первый <br/>            DWORD этих данных НЕ ДОЛЖЕН быть одним из предопределённых значений идентификатора комментария, указанных <br/>            в разделе 2.3.3.<br/>            Закрытые данные неизвестны EMF; они имеют смысл только для приложений, которые знают формат <br/>            данных и как их использовать. Записи закрытых данных EMR_COMMENT МОГУТ быть проигнорированы. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfComment(source) {#EmfComment_source_1}


```
 EmfComment(source) 
```

Инициализирует новый экземпляр класса [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/).

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


