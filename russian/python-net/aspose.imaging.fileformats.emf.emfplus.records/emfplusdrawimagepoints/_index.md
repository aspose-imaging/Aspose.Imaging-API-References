---
title: "Класс EmfPlusDrawImagePoints"
type: docs
weight: 140
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Получает или задает значение, указывающее, применяется ли [applying an effect].<br/>            Этот бит указывает, что визуализация изображения включает применение эффекта.<br/>            Если установлен, объект класса Effect ДОЛЖЕН быть указан в более ранней записи EmfPlusSerializableObject (section 2.3.5.2). |
| сжатый | bool | r/w | Получает или задает значение, указывающее, сжаты ли данные PointData.<br/>            Этот бит указывает, задает ли поле PointData сжатые данные.<br/>            Если установлен, PointData задает абсолютные координаты в пространстве с 16-битными целочисленными координатами.<br/>            Если сброшен, PointData задает абсолютные координаты в пространстве с 32-битными координатами с плавающей точкой.<br/>            Примечание: если установлен флаг P (ниже), этот флаг не определён и ДОЛЖЕН быть проигнорирован. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| image_attributes_id | int | r/w | Получает или задает 32-битное беззнаковое целое, содержащее индекс<br/>            необязательного объекта EmfPlusImageAttributes (section 2.2.1.5) в таблице объектов EMF+. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusImage (section 2.2.1.4) в таблице объектов EMF+<br/>            , который определяет изображение для отрисовки. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает массив из Count точек, определяющих три вершины параллелограмма.<br/>            Три точки представляют верхний‑левый, верхний‑правый и нижний‑левый углы<br/>            параллелограмма. Четвёртая вершина параллелограмма вычисляется из первых трёх. Часть изображения, указанная полем SrcRect, ДОЛЖНА иметь применённые масштабирование и сдвиг (shearing) преобразования, если это необходимо, чтобы поместиться внутри параллелограмма. |
| relative | bool | r/w | Получает или задает значение, указывающее, является ли этот [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) относительным.<br/>            Этот бит указывает, задаёт ли поле PointData относительные или абсолютные координаты.<br/>            Если установлен, каждый элемент в PointData задает положение в пространстве координат, которое является<br/>            относительным к положению, указанному предыдущим элементом массива. В случае первого<br/>            элемента PointData предполагается предыдущее положение с координатами (0,0). Если сброшен,<br/>            PointData задает абсолютные координаты согласно флагу C.<br/>            Примечание: если этот флаг установлен, флаг C (выше) не определён и ДОЛЖЕН быть проигнорирован. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает объект EmfPlusRectF (section 2.2.2.39), определяющий часть изображения для отрисовки. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Получает или задает 32-битное знаковое целое, определяющее единицы измерения поля SrcRect. Оно ДОЛЖНО<br/>            быть значением UnitPixel перечисления UnitType (section 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

