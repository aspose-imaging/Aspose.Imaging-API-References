---
title: "Класс EmfCommentPublicRecordType"
type: docs
weight: 220
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---

**Summary:** The EMR_COMMENT_PUBLIC record types specify extensions to EMF processing.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType

**Inheritance:** EmfCommentRecordType

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Получает или задает 32-битное беззнаковое целое, которое идентифицирует эту запись комментария <br/> как содержащую публичные данные. Значение 0x43494447, которое является ASCII‑строкой \"CIDG\", идентифицирует <br/> её как запись EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает размер в байтах полей <br/>            CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое <br/>            следует. Оно НЕ ДОЛЖНО включать размер самого себя или размер поля AlignmentPadding, если <br/>            оно присутствует. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет тип <br/> публичной записи комментария. Это ДОЛЖНО быть одним из значений, перечисленных в предыдущей таблице, которые <br/> указаны в перечислении EmrComment (раздел 2.1.10), если только дополнительные типы публичных <br/> записей комментариев не были реализованы на сервере печати. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


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


