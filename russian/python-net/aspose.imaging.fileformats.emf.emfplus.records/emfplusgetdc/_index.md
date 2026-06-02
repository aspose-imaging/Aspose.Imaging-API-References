---
title: "Класс EmfPlusGetDc"
type: docs
weight: 300
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---

**Summary:** The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusGetDc

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusGetDc(source)](#EmfPlusGetDc_source_1) | Создаёт новый экземпляр класса [EmfPlusGetDc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, которое не используется. Это поле ДОЛЖНО быть установлено в ноль<br/>            и ДОЛЖНО игнорироваться при получении. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusGetDc(source) {#EmfPlusGetDc_source_1}


```
 EmfPlusGetDc(source) 
```

Создаёт новый экземпляр класса [EmfPlusGetDc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

