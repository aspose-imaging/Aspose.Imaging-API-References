---
title: "Класс EmfPlusEndContainer"
type: docs
weight: 210
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---

**Summary:** The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusEndContainer(source)](#EmfPlusEndContainer_source_1) | Инициализирует новый экземпляр класса [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| stack_index | int | r/w | Получает или задает 32‑битное беззнаковое целое, указывающее индекс контейнера состояния графики<br/>            . Индекс ДОЛЖЕН соответствовать значению, связанному с контейнером состояния графики,<br/>            открытым предыдущей записью EmfPlusBeginContainer (раздел 2.3.7.1) или<br/>            записью EmfPlusBeginContainerNoParams (раздел 2.3.7.2). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusEndContainer(source) {#EmfPlusEndContainer_source_1}


```
 EmfPlusEndContainer(source) 
```

Инициализирует новый экземпляр класса [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

