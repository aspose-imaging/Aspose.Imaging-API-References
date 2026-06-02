---
title: "EmfPlusResetClip Class"
type: docs
weight: 380
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetclip/
---

**Summary:** The EmfPlusResetClip record resets the current clipping region for the world space to infinity.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusResetClip

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusResetClip(source)](#EmfPlusResetClip_source_1) | Инициализирует новый экземпляр класса [EmfPlusResetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusResetClip(source) {#EmfPlusResetClip_source_1}


```
 EmfPlusResetClip(source) 
```

Инициализирует новый экземпляр класса [EmfPlusResetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetclip/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

