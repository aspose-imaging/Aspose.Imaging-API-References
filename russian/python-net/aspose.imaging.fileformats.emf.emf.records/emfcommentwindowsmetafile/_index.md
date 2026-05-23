---
title: "Класс EmfCommentWindowsMetaFile"
type: docs
weight: 240
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

**Summary:** The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentWindowsMetaFile(source)](#EmfCommentWindowsMetaFile_source_1) | Инициализирует новый экземпляр класса [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| checksum | int | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет контрольную сумму для этой записи. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Получает или задает 32-битное беззнаковое целое, которое идентифицирует эту запись комментария <br/> как содержащую публичные данные. Значение 0x43494447, которое является ASCII‑строкой \"CIDG\", идентифицирует <br/> её как запись EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает размер в байтах полей <br/>            CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое <br/>            следует. Оно НЕ ДОЛЖНО включать размер самого себя или размер поля AlignmentPadding, если <br/>            оно присутствует. |
| flags | int | r/w | Получает или задает 32-битное значение, которое ДОЛЖНО быть 0x00000000 и ДОЛЖНО игнорироваться. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет тип <br/> публичной записи комментария. Это ДОЛЖНО быть одним из значений, перечисленных в предыдущей таблице, которые <br/> указаны в перечислении EmrComment (раздел 2.1.10), если только дополнительные типы публичных <br/> записей комментариев не были реализованы на сервере печати. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| version | [WmfMetafileVersion](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileversion/) | r/w | Получает или задает 16-битное беззнаковое целое, которое определяет версию WMF метафайла в терминах <br/>            поддержки независимых от устройства битмапов (DIB), из перечисления WMF MetafileVersion <br/>            ([MS-WMF] раздел 2.1.1.19). |
| win_metafile | [MetaImage](/imaging/python-net/aspose.imaging.fileformats.emf/metaimage/) | r/w | Получает или задает буфер, содержащий WMF метафайл. |
| win_metafile_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет размер в байтах <br/>            WMF метафайла в поле WinMetafile. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentWindowsMetaFile(source) {#EmfCommentWindowsMetaFile_source_1}


```
 EmfCommentWindowsMetaFile(source) 
```

Инициализирует новый экземпляр класса [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/).

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


