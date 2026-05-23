---
title: "Класс EmfPlusDrawPie"
type: docs
weight: 170
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---

**Summary:** The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawPie(source)](#EmfPlusDrawPie_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| сжатый | bool | r/w | Получает или задает значение, указывающее, сжаты ли данные PointData.<br/>            Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38).<br/>            Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39). |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+<br/>            для отрисовки сектора. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает данные прямоугольника<br/>            Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник <br/>            эллипса, содержащего сектор. Этот прямоугольник определяет положение, размер <br/>            и форму сектора. Тип объекта в этом поле задаётся значением <br/>            поля Flags. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| start_angle | float | r/w | Получает или задает начальный угол<br/>            32‑битное неотрицательное число с плавающей запятой, определяющее угол между <br/>            осью X и начальной точкой сектора. Любое значение допускается, но оно <br/>            ДОЛЖНО интерпретироваться по модулю 360, при этом используемый результат находится в диапазоне <br/>            от 0,0 включительно до 360,0 исключая верхнюю границу. |
| sweep_angle | float | r/w | Получает или задает угол разворота<br/>            32‑битное число с плавающей запятой, определяющее протяжённость дуги, задающей <br/>            сектор для рисования, как угол в градусах, измеряемый от начальной точки, <br/>            определённой значением StartAngle. Любое значение допускается, но оно ДОЛЖНО быть ограничено <br/>            диапазоном от -360,0 до 360,0 включительно. Положительное значение указывает, что разворот определён <br/>            по часовой стрелке, а отрицательное — против часовой стрелки. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawPie(source) {#EmfPlusDrawPie_source_1}


```
 EmfPlusDrawPie(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

