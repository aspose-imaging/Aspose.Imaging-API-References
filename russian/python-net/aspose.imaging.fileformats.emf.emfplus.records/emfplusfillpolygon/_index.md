---
title: "Класс EmfPlusFillPolygon"
type: docs
weight: 270
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Создаёт новый экземпляр класса [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Получает или задает идентификатор кисти<br/>            32-битное беззнаковое целое, определяющее кисть, содержимое <br/>            которой определяется битом S в поле Flags. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| is_color | bool | r/w | Получает или задает значение, указывающее, является ли этот экземпляр цветом.<br/>            Если установлено, BrushId задаёт цвет как объект EmfPlusARGB (section 2.2.2.1). <br/>            Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (section 2.2.1.1) в таблице EMF+ Object Table. |
| is_compressed | bool | r/w | Получает или задает значение, указывающее, сжат ли этот экземпляр.<br/>            Если установлено, PointData задаёт абсолютные координаты в пространстве с 16-битными <br/>            целочисленными координатами. Если сброшено, PointData задаёт абсолютные координаты в пространстве с 32-битными координатами с плавающей точкой. |
| is_relative | bool | r/w | Получает или задает значение, указывающее, является ли этот экземпляр относительным.<br/>            Если установлено, каждый элемент в PointData задаёт положение в координатном <br/>            пространстве, относительно положения, указанного предыдущим элементом <br/>            массива. Для первого элемента в PointData предполагается предыдущее <br/>            положение с координатами (0,0). Если сброшено, PointData задаёт <br/>            абсолютные положения согласно флагу C. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает данные точек<br/>            Массив из Count точек, определяющих вершины многоугольника. <br/>            Первые две точки в массиве задают первую сторону многоугольника. <br/>            Каждая последующая точка задаёт новую сторону, вершины которой <br/>            включают текущую точку и предыдущую точку. Если последняя точка и <br/>            первая точка не совпадают, они задают последнюю сторону многоугольника. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Создаёт новый экземпляр класса [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

