---
title: "Класс EmfPlusDrawRects"
type: docs
weight: 180
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---

**Summary:** The EmfPlusDrawRects record specifies drawing a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawRects(source)](#EmfPlusDrawRects_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| сжатый | bool | r/w | Получает или задает значение, указывающее, сжаты ли данные PointData.<br/>            Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38).<br/>            Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39). |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+<br/>            для рисования прямоугольников. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает данные прямоугольника<br/>            Массив объектов EmfPlusRect или EmfPlusRectF длиной Count, определяющий данные прямоугольника. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawRects(source) {#EmfPlusDrawRects_source_1}


```
 EmfPlusDrawRects(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

