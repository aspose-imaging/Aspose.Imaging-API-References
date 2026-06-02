---
title: "EmfPlusSetClipRegion Класс"
type: docs
weight: 480
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---

**Summary:** The EmfPlusSetClipRegion record combines the current clipping region with another graphics region.<br/>            The new current clipping region is set to the result of performing the CombineMode operation on<br/>            the previous current clipping region and the specified EmfPlusRegion object.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRegion

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetClipRegion(source)](#EmfPlusSetClipRegion_source_1) | Инициализирует новый экземпляр класса [EmfPlusSetClipRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | Получает или задает CM (4 бита): определяет логическую операцию для объединения двух регионов. См. <br/>            CombineMode enumeration (section 2.1.1.4) для значений. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| object_id | System.Byte | r/w | Получает или задает индекс объекта EmfPlusRegion (section 2.2.1.8) в таблице EMF+<br/>            Object Table. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusSetClipRegion(source) {#EmfPlusSetClipRegion_source_1}


```
 EmfPlusSetClipRegion(source) 
```

Инициализирует новый экземпляр класса [EmfPlusSetClipRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

