---
title: "EmfPlusFillClosedCurve Класс"
type: docs
weight: 230
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Инициализирует новый экземпляр класса [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Получает или задает идентификатор кисти<br/>            32-битное беззнаковое целое, которое указывает EmfPlusBrush, содержимое которого <br/>            определяется битом S в поле Flags. Эта кисть используется для заполнения внутренней части <br/>            замкнутого кардинального сплайна. |
| compressed | bool | r/w | Получает или задает значение, указывающее, сжат ли этот [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/).<br/>            Этот бит указывает, задает ли поле PointData сжатые данные.<br/>            Если установлен, PointData задает абсолютные положения в координатном пространстве с 16-битными <br/>            целочисленными координатами. Если сброшен, PointData задает абсолютные положения в <br/>            координатном пространстве с 32-битными координатами с плавающей точкой.<br/>            ----------------------<br/>            Операция заполнения "winding" заполняет области согласно правилу "четно-нечетной четности". <br/>            Согласно этому правилу, тестовая точка может быть определена как находящаяся внутри или снаружи <br/>            замкнутой кривой следующим образом: проведите линию от тестовой точки к точке, удалённой <br/>            от кривой. Если эта линия пересекает кривую нечетное число раз, тестовая <br/>            точка находится внутри кривой; иначе тестовая точка находится снаружи кривой.<br/>            ---------------------<br/>            Операция заполнения "alternate" заполняет области согласно правилу "не ноль".<br/>            Согласно этому правилу, тестовая точка может быть определена как находящаяся внутри или снаружи <br/>            замкнутой кривой следующим образом: проведите линию от тестовой точки к точке, <br/>            удалённой от кривой. Подсчитайте количество пересечений кривой с тестовой <br/>            линией слева направо и количество пересечений кривой с тестовой <br/>            линией справа налево. Если эти два числа одинаковы, тестовая точка <br/>            находится снаружи кривой; иначе тестовая точка находится внутри кривой. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| is_color | bool | r/w | Получает или задает значение, указывающее, является ли данный экземпляр цветным.<br/>            Если установлено, BrushId задает цвет как объект EmfPlusARGB (раздел 2.2.2.1).<br/>            Если сброшено, BrushId содержит индекс объекта EmfPlusBrush <br/>            (раздел 2.2.1.1) в таблице объектов EMF+. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает данные точек<br/>            Массив из Count точек, определяющих конечные точки линий, образующих сплайн. <br/>            В замкнутом кардинальном сплайне кривая продолжается через последнюю точку в массиве PointData <br/>            и соединяется с первой точкой в массиве. |
| relative | bool | r/w | Получает или задает значение, указывающее, является ли этот [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) относительным.<br/>            Этот бит указывает, задает ли поле PointData относительные или абсолютные положения.<br/>            Если установлен, каждый элемент в PointData указывает расположение в координатном пространстве, которое<br/>            относительно расположения, указанного предыдущим элементом в массиве. В случае <br/>            первого элемента в PointData предполагается предыдущее расположение с координатами (0,0). <br/>            Если сброшен, PointData задает абсолютные положения согласно флагу C.<br/>            Примечание: если этот флаг установлен, флаг C (выше) не определён и ДОЛЖЕН игнорироваться. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| натяжение | float | r/w | Получает или задает натяжение<br/>            32-битное значение с плавающей точкой, которое указывает, насколько сильно изгибается сплайн при прохождении <br/>            через точки. Значение 0.0 указывает, что сплайн представляет собой последовательность прямых <br/>            линий. По мере увеличения значения кривая становится более округлой. Для получения дополнительной информации <br/>            см. [SPLINE77] и [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |
| winding | bool | r/w | Получает или задает значение, указывающее, является ли этот [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) winding.<br/>            Этот бит указывает, как выполнять операцию заполнения.<br/>            Если установлен, заполнение выполняется как "winding". Если сброшен, заполнение выполняется как "alternate". |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Инициализирует новый экземпляр класса [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

