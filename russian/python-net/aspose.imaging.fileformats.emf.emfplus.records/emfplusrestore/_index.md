---
title: "EmfPlusRestore Класс"
type: docs
weight: 400
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---

**Summary:** The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRestore

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusRestore(source)](#EmfPlusRestore_source_1) | Инициализирует новый экземпляр класса [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| stack_index | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает уровень, связанный с <br/> графическим состоянием. Значение уровня было присвоено графическому состоянию предыдущей записью EmfPlusSave (раздел 2.3.7.5). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusRestore(source) {#EmfPlusRestore_source_1}


```
 EmfPlusRestore(source) 
```

Инициализирует новый экземпляр класса [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

