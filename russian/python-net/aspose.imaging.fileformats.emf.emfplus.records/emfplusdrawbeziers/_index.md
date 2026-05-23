---
title: "Класс EmfPlusDrawBeziers"
type: docs
weight: 80
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| сжатый | bool | r/w | Получает или задает значение, указывающее, сжаты ли данные PointData. <br/>            Если установлено, PointData задает абсолютные координаты в пространстве с <br/>            16-битными целочисленными координатами. Если сброшено, PointData задает абсолютные координаты <br/>            в пространстве с 32-битными координатами с плавающей точкой.<br/>            Примечание: если установлен флаг Relative (ниже), этот флаг не определён и ДОЛЖЕН быть проигнорирован. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusPen (section 2.2.1.7) в таблице объектов EMF+<br/>            для отрисовки кривых Безье. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает данные точек<br/>            Массив из Count точек, определяющих начальные, конечные и контрольные точки кривых Безье. Конечная координата одной кривой Безье является начальной координатой следующей. Контрольные точки используются для создания эффекта Безье.<br/>            Тип данных в этом массиве задаётся полем Flags следующим образом: Значение типа данных<br/>            объект EmfPlusPointR (section 2.2.2.37)<br/>            Если в Flags установлен флаг P, точки задают относительные положения.<br/>            объект EmfPlusPointF (section 2.2.2.36)<br/>            Если биты P и C сброшены в поле Flags, точки задают абсолютные положения.<br/>            объект EmfPlusPoint (section 2.2.2.35)<br/>            Если бит P сброшен, а бит C установлен в поле Flags, точки задают относительные положения.<br/>            Кривая Безье не проходит через свои контрольные точки. Контрольные точки действуют как |
| relative | bool | r/w | Получает или задает значение, указывающее, является ли PointData относительным.<br/>            Если установлено, каждый элемент в PointData указывает расположение в координатном пространстве <br/>            относительно расположения, указанного предыдущим элементом в массиве. <br/>            В случае первого элемента в PointData предполагается предыдущее расположение с координатами <br/>            (0,0). Если сброшено, PointData указывает абсолютные положения в соответствии <br/>            с флагом C.<br/>            Примечание: если этот флаг установлен, флаг C (выше) не определён и ДОЛЖЕН игнорироваться. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

