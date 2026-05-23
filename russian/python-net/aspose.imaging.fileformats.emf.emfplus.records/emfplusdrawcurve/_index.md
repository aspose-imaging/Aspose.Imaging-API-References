---
title: "Класс EmfPlusDrawCurve"
type: docs
weight: 100
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Получает или задает значение, указывающее, сжат ли этот [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            Этот бит указывает, задает ли поле PointData сжатые данные.<br/>            Если установлен, PointData задает абсолютные положения в координатном пространстве с 16‑битными целочисленными координатами. <br/>            Если сброшен, PointData задает абсолютные положения в координатном пространстве с 32‑битными координатами с плавающей запятой.<br/>            Примечание: если установлен флаг Relative (ниже), этот флаг не определён и ДОЛЖЕН игнорироваться |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| num_segments | int | r/w | Получает или задает количество сегментов <br/> A 32‑битное беззнаковое целое, которое указывает число линейных сегментов, составляющих сплайн. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/> Индекс объекта EmfPlusPen (раздел 2.2.1.7) в EMF+<br/> таблице объектов для рисования кривой. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает массив, состоящий из 32‑битных знаковых целых или 32‑битных чисел с плавающей точкой длиной Count, определяющий координаты конечных точек линий для обводки. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| натяжение | float | r/w | Получает или задает натяжение<br/>            32‑разрядное число с плавающей точкой, определяющее, насколько сильно сплайн <br/>            изгибается при прохождении через точки. Значение 0 указывает, что <br/>            сплайн представляет собой последовательность прямых линий. По мере увеличения значения <br/>            кривая становится более округлой. Для получения дополнительной информации см. [SPLINE77] и [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

