---
title: "Класс EmfPlusDrawArc"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает размер данных.<br/>            32-битное беззнаковое целое, указывающее количество байтов специфичных для записи, выровненное по 32-битам,<br/>            которые следуют.<br/>            Для этого типа записи значение ДОЛЖНО быть одним из следующих:<br/>            0x00000010 Если бит C установлен в поле Flags.<br/>            0x00000018 Если бит C сброшен в поле Flags. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для отрисовки дуги. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| rect_float | bool | r/w | Получает или задает значение, указывающее, содержит ли данные <br/>            записи EmfPlusRectF или EmfPlusRect.<br/>            Этот бит указывает, сжаты ли данные в поле RectData.<br/>            Если установлен, RectData содержит объект EmfPlusRect (раздел 2.2.2.38).<br/>            Если сброшен, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает данные прямоугольника<br/>            Это объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник<br/>            эллипса, коллинеарного дуге. Этот прямоугольник задает<br/>            положение, размер и форму дуги. Тип объекта в этом поле определяется<br/>            значением поля Flags. |
| size | int | r/w | Получает или задает размер.<br/>            32-битное беззнаковое целое, указывающее количество байтов во всей записи, выровненное по 32-битам,<br/>            включая 12-байтовый заголовок записи и данные, специфичные для записи. Для этого типа записи значение ДОЛЖНО быть одним из следующих:<br/>            0x0000001C  Если бит C установлен в поле Flags.<br/>            0x00000024  Если бит C сброшен в поле Flags. |
| start_angle | float | r/w | Получает или задает начальный угол<br/>            32-битное неотрицательное число с плавающей запятой, определяющее угол между<br/>            осью X и начальной точкой дуги. Любое значение допускается,<br/>            но оно ДОЛЖНО интерпретироваться по модулю 360, при этом используемый результат находится<br/>            в диапазоне от 0,0 включительно до 360,0 исключая. |
| sweep_angle | float | r/w | Получает или задает угол разворота<br/>            32-битное число с плавающей запятой, определяющее протяжённость дуги для отрисовки,<br/>            как угол в градусах, измеряемый от начальной точки, определённой значением<br/>            StartAngle. Любое значение допускается, но оно ДОЛЖНО быть ограничено диапазоном от -360,0<br/>            до 360,0 включительно. Положительное значение указывает, что разворот определяется<br/>            по часовой стрелке, а отрицательное — против часовой стрелки. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

