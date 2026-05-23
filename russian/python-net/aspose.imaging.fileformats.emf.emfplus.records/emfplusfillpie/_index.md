---
title: "Класс EmfPlusFillPie"
type: docs
weight: 260
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---

**Summary:** The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillPie(source)](#EmfPlusFillPie_source_1) | Инициализирует новый экземпляр класса [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Получает или задает идентификатор кисти<br/>            32‑разрядное беззнаковое целое, определяющее кисть, содержимое которой <br/>            определяется битом S в поле Flags. |
| сжатый | bool | r/w | Получает или задает значение, указывающее, сжаты ли данные PointData.<br/>            Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38).<br/>            Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39). |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| is_color | bool | r/w | Получает или задает значение, указывающее, является ли этот экземпляр цветом.<br/>            Если установлено, BrushId задаёт цвет как объект EmfPlusARGB (section 2.2.2.1). <br/>            Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (section 2.2.1.1) в таблице EMF+ Object Table. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает данные прямоугольника<br/>            Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник <br/>            эллипса, содержащего сектор. Этот прямоугольник определяет положение, размер <br/>            и форму сектора. Тип объекта в этом поле задаётся значением <br/>            поля Flags. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| start_angle | float | r/w | Получает или задает начальный угол<br/>            32‑битное неотрицательное число с плавающей запятой, определяющее угол между <br/>            осью X и начальной точкой сектора. Любое значение допускается, но оно <br/>            ДОЛЖНО интерпретироваться по модулю 360, при этом используемый результат находится в диапазоне <br/>            от 0,0 включительно до 360,0 исключая верхнюю границу. |
| sweep_angle | float | r/w | Получает или задает угол разворота<br/>            32‑битное число с плавающей запятой, определяющее протяжённость дуги, задающей <br/>            сектор для рисования, как угол в градусах, измеряемый от начальной точки, <br/>            определённой значением StartAngle. Любое значение допускается, но оно ДОЛЖНО быть ограничено <br/>            диапазоном от -360,0 до 360,0 включительно. Положительное значение указывает, что разворот определён <br/>            по часовой стрелке, а отрицательное — против часовой стрелки. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusFillPie(source) {#EmfPlusFillPie_source_1}


```
 EmfPlusFillPie(source) 
```

Инициализирует новый экземпляр класса [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

