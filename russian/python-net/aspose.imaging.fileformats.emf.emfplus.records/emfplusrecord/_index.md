---
title: "Класс EmfPlusRecord"
type: docs
weight: 370
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---

**Summary:** The Emf+ base record type.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusRecord()](#EmfPlusRecord__1) | Инициализирует новый экземпляр класса [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/). |
| [EmfPlusRecord(source)](#EmfPlusRecord_source_2) | Инициализирует новый экземпляр класса [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusRecord() {#EmfPlusRecord__1}


```
 EmfPlusRecord() 
```

Инициализирует новый экземпляр класса [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/).

### Constructor: EmfPlusRecord(source) {#EmfPlusRecord_source_2}


```
 EmfPlusRecord(source) 
```

Инициализирует новый экземпляр класса [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

