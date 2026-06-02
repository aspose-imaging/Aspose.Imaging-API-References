---
title: "Класс EmfPlusEndOfFile"
type: docs
weight: 220
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---

**Summary:** The EmfPlusEndOfFile record specifies the end of EMF+ data in the metafile.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndOfFile

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusEndOfFile(source)](#EmfPlusEndOfFile_source_1) | Инициализирует новый экземпляр класса [EmfPlusEndOfFile](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, которое не используется. Это поле ДОЛЖНО быть установлено в ноль<br/>            и ДОЛЖНО игнорироваться при получении. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusEndOfFile(source) {#EmfPlusEndOfFile_source_1}


```
 EmfPlusEndOfFile(source) 
```

Инициализирует новый экземпляр класса [EmfPlusEndOfFile](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

