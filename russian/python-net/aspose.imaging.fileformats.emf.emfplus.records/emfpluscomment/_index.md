---
title: "Класс EmfPlusComment"
type: docs
weight: 50
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---

**Summary:** The EmfPlusComment record specifies arbitrary private data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusComment

**Inheritance:** EmfPlusRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusComment(source)](#EmfPlusComment_source_1) | Инициализирует новый экземпляр класса [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, которое не используется. Это поле ДОЛЖНО быть установлено в ноль<br/>            и ДОЛЖНО игнорироваться при получении. |
| private_data | System.Byte | r/w | Получает или задает байтовый массив длиной DataSize, содержащий закрытые данные.<br/> байты специфичных для записи данных, которые следуют. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusComment(source) {#EmfPlusComment_source_1}


```
 EmfPlusComment(source) 
```

Инициализирует новый экземпляр класса [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

