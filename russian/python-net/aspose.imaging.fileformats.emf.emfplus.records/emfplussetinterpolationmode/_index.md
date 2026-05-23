---
title: "Класс EmfPlusSetInterpolationMode"
type: docs
weight: 510
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---

**Summary:** The EmfPlusSetInterpolationMode record specifies how image scaling, including stretching and shrinking, is performed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetInterpolationMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetInterpolationMode(source)](#EmfPlusSetInterpolationMode_source_1) | Инициализирует новый экземпляр класса [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| interpolation_mode | [EmfPlusInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/) | r/w | Получает или задает значение режима интерполяции из перечисления InterpolationMode (раздел 2.1.1.16). |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusSetInterpolationMode(source) {#EmfPlusSetInterpolationMode_source_1}


```
 EmfPlusSetInterpolationMode(source) 
```

Инициализирует новый экземпляр класса [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

