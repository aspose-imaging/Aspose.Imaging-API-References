---
title: "Класс EmfPlusDrawLines"
type: docs
weight: 150
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Получает или задает значение, указывающее, является ли [closed shape]. |
| compressed | bool | r/w | Получает или задает значение, указывающее, сжат ли этот [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            Этот бит указывает, задает ли поле PointData сжатые данные.<br/>            Если установлен, PointData задает абсолютные положения в координатном пространстве с 16‑битными целочисленными координатами. <br/>            Если сброшен, PointData задает абсолютные положения в координатном пространстве с 32‑битными координатами с плавающей запятой.<br/>            Примечание: если установлен флаг Relative (ниже), этот флаг не определён и ДОЛЖЕН игнорироваться |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+<br/>            для отрисовки линий. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает данные точек<br/>            Массив из Count точек, определяющих начальные и конечные точки линий для отрисовки. |
| relative | bool | r/w | Получает или задает значение, указывающее, является ли этот [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) относительным.<br/>            Этот бит указывает, задает ли поле PointData относительные или абсолютные положения.<br/>            Если установлен, каждый элемент в PointData задает положение в координатном пространстве, которое является относительным <br/>            к положению, указанному предыдущим элементом в массиве. В случае первого <br/>            элемента в PointData предполагается предыдущее положение с координатами (0,0). Если сброшен, <br/>            PointData задает абсолютные положения согласно флагу C.<br/>            Примечание: если этот флаг установлен, флаг Compressed (выше) не определён и ДОЛЖЕН игнорироваться |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

